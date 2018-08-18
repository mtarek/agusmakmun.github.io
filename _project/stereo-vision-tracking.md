---
layout: project_single
title:  "Guiding ophthalmic surgery using OCT and stereo-vision tracking of surgical instruments"
slug: "stereo-vision-tracking"
---

There has been a plethora of research over the past decade to bring OCT to the ophthalmic surigcal suite. The reason being that, until recently, the surgeons only had access to surface views of the retina through the traditional surgical microscope so it was not possible to know what was happening below the surface in the operating room. 

The advent of the first handheld imaging probe provided the surgeons with the ability to visualize the different retinal layers at surgical regions-of-interest (ROIs) before and after manipulation of the tissue, or "perioperatively". As you can imagine, holding a probe over a patient's pupil that's only a couple of millimeters in diameter to image a cross-section at a specific ROI is not straightforward. Further developments thus focused on enhanced ergonomics and better integration with the surgical workflow. This led to the development of micrscope-mounted probes which provided better stability and control, but still required pausing the surgery and finding the ROI. The next generation of intraoperative OCT (iOCT - not to be confused with any commercial brands) featured scan-heads that were fully integrated with the surgical microscope both mechanically and optically. This was a rather clever approach that alleviated many of the previous limitations; it made steering the OCT field much easier, and significantly reduced the overhead required to acquire the tomograms. However, OCT was still essentially imaging a single plane in depth (XZ, as oppoed to XY in a conventional microscope). The implication of which was that, unless the motion was only within the XZ plane, it was difficult to maintain the surgical instrument with the OCT field-of-view (FOV) at all times. 

My PhD focuses on developing systems and methods to address these (and other) limitations with the goal of making iOCT more amenable to large-scale adoption. 

Here are two review papers that describe with more detail what I just said:
1. Review in Biomedical Optics Express by Oscar Carrasco-Zevallous
2. My review paper in Current Opinion in Biomedical Engineering

What I've worked on:
1. Development of a stereo-vision tracking system, to track surgical instruments and steer the OCT field accordingly.
    - While this showed promising performance for corneal surgery, it was difficult to translate to retinal surgery since the refractive power of the patient's eye makes it such that the stereo FOV and the OCT FOV would need to be calibrated _per eye_, this led to
2. A multimodal imaging system, which images with similar contrast in both XY and XZ planes. The images are coregistered in space and time by design, and the total throughput exceeded 2.2 GPix/s.
3. A method for _reverse engineering_ of the surigcal microscope objective
4. Deep learning based tracking for selective high-density sampling of the OCT FOV.