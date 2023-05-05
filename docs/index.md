---
layout: default
title: Overview
nav_order: 1
---

# Alzheimer Imaging Consortium Educational Workshop
## Getting started With Neuroimaging Analysis

### Details

|  |  |
| --- | --- |
| Date | Friday 14th July 2023 |
| Time | 8-12 AM GMT+2 | 
| Location | Amsterdam, Netherlands |
| Format | In-person workshop | 

### Target Audience
This hands-on workshop can serve as a beginner or refresher course for established investigators, clinicians, and trainees involved in the use of imaging techniques in the study of Alzheimer’s disease, related disorders and normal aging. Participants from any career stage are encouraged to join, including undergraduate students, graduate students, post-doctoral researchers and assistant professors engaged in clinical practice, research or teaching.

### Requirements
Registrants will need to bring their own laptop to do the exercises (tablets or smartphones will not be sufficient). They will be provided with this repository and links to the "Basics of Neuroimaging" series of AAIC webinars that are occuring in April 2023. The links to the webinars and the slides are below.
| Webinar Tite | Slides |
| --- | --- |
| [Data Structure and Formats](https://training.alz.org/products/4520/neuroimaging-pia-basics-of-neuroimaging-data-structure-and-formats) |[Slides](./assets/1_BasicsNeuroimaging_StructureFormat-Griffanti.pdf) | 
| [The Basics of Neuroimaging: Structural Magnetic Resonance Imaging (MRI)](https://training.alz.org/products/4524/neuroimaging-pia-the-basics-of-neuroimaging-structural-magnetic-resonance-imaging-mri) | [Slides](./assets/2_BasicsNeuroimaging_StructuralMRI-Cash.pdf) | 
| [Positron emission tomography (PET)](https://training.alz.org/products/4525/neuroimaging-pia-the-basics-of-neuroimaging-positron-emission-tomography-pet) | [Slides](./assets/3_BasicsNeuroimaging_PET-Betthauser.pdf) |
| [Diffusion-Weighted Imaging (DWI)](https://training.alz.org/products/4526/neuroimaging-pia-the-basics-of-neuroimaging-diffusion-weighted-imaging-dwi) | [Slides](./assets/4_BasicsNeuroimaging_Diffusion_AlexaPB.pdf) |
| Functional Magnetic Resonance Imaging (fMRI) - webinar link coming soon | [Slides](./assets/5_BasicsNeuroimaging_Functional_Luigi.pdf) |

At the workshop,we will all be using a standard environment, using a virtual machine (VM) hostedn on  the cloud. This ensures that everyone will be seeing the exact same screen for these lessons, regardless of if you are using a Mac or Windows operating system. You can find out more how to access this virtual machine in the [Connecting](./connecting.md) section.

### Workshop description
The workshop will provide practical information and an enhanced understanding on how to work with and analyze medical imaging data from magnetic resonance imaging (MRI) and positron imaging tomography (PET).

The initial portion of the workshop will focus on the understanding of the basic structure of an image, how to traverse images, data extraction, and how voxels relate to world coordinates.

Subsequent lectures will be followed by interactive sessions to demonstrate simple workflows including tissue segmentation, registration, and pre-processing steps of fMRI or DTI. The objective of the workshop is to ensure participants gain an in-depth appreciation of commonly used interpretive clinical and or research applications for each methodology. 


### Agenda
The workshop will consist of hands-on interactive sessions. The first session will focus on understanding of the basic structure of imaging data, how to traverse images, data extraction, and how voxels relate to world coordinates. We will then go through the basic processing steps involving structural MRI data, demonstrating simple workflows including tissue segmentation, and registration. The second half will consist of two independent working sessions, where facilitators will present interactive tutorials around different forms of neuroimaging analysis (structural MRI, fMRI, DTI or PET data), and the participants will then work on the tutorials of their choice, with assistance from the facilitators. The objective of the workshop is to ensure participants gain an understanding of how to start processing and analyzing various imaging modalities used in dementia research. 



| Time | Topic | Leader(s) | 
| --- | --- | --- |
| 8:00-8:10 AM | Opening Remarks | David Cash and Tobey Betthauser |
| 8:10-8:40 AM |  [Image data: Basic Structure and Function](./imaging-data.md) | Ludovica Griffanti | 
| 8:40-9:10 AM| [Structural MRI](./structural-mri.md) | David Cash | 
| 9:10-9:20 AM | Break | |
| 9:20-9:50 AM | Introduction to Advanced Imaging Analysis Sections (PET,DT,fMRI) | Tobey Betthauser, Alexa Pichet Binette, Luigi Lorenzini |
| 9:50-10:40 AM | Independent working session 1: [dMRI](./dmri-preproc.md), [fMRI](./fmri-preproc.md) or [PET](./pet.md)  | Facilitated by all organizers |
| 10:40-11:50 AM | Break | |
| 10:50-11:40 AM | Independent working session 2: [dMRI](./dmri-preproc.md), [fMRI](./fmri-preproc.md) or [PET](./pet.md)   | Facilitated by all organizers |
| 11:40 AM - 12:00 PM | Wrapup, Q&A, feedback | David Cash and Tobey Betthauser |


### Additional material
Lessons and information that are helpful, but not part of the workshop can be found below:
* [Getting started with the command line](./command-line.md): Many neuroimaging software packages do not use a graphical interface but require you to be comfortable typing in commands into the computer. This section gives an overview of some basic commands and how to traverse a Linux filesystem.

### Organizing Committee
The following committee members have been developing and testing the content, and will be on-hand to lead the sessions and assist individuals. 

| Name | Organization |
| --- | --- |
| David M. Cash, Ph.D. | UCL Queen Square Institute of Neurology, United Kingdom
| Luigi Lorenzini | Amsterdam UMC, Netherlands |
| Ludovica Griffanti | University of Oxford, United Kingdom |
| Tobey Betthauser | University of Wisconsin, U.S.A. | 
| Alexa Pichet Binette | Lund University, Sweden |

### Acknowledgements
These lessons are developed as part of the [Health and Biosciences IDEAS](https://healthbioscienceideas.github.io) project, which is a training initiative funded by [UKRI Innovation Scholars](https://www.ukri.org/opportunity/innovation-scholars-data-science-training-in-health-bioscience/) (MR/V03863X/1)

Thanks to the generous support of the Alzheimer's Association, the [International Society to Advance Alzheimer's Research and Treatment (ISTAART)](https://action.alz.org/personifyebusiness/default.aspx?tabid=1516) and the ISTAART Neuroimaging Professional Interest Area in terms of travel funding for the organizers.

The data for this course comes from the [Open Access Series of Imaging Studies](https://www.oasis-brains.org/)(OASIS) dataset. Many thanks to Pamela LaMontaigne and the OASIS team as Washington University for their support with the data.

Special thanks to Christian Haselgrove (NITRC-CE), Courtney Waugh (Amazon), and Mark Watts (UCL) for their support in creating the infrastructure for this project. 
