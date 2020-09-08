# Awesome Biomechanics 

## [Still a Work In Progress (includes incomplete descriptions) - feel free of contributing]

## Table of contents

- [Online Courses :clapper:](#online-courses-clapper)
- [YouTube Channels :tv:](#youtube-channels-tv)
- [Videos :video_camera:](#videos-video_camera)
- [Teaching Resources :triangular_ruler:](#teaching-resources-triangular_ruler)
- [Books :blue_book:](#books-blue_book)
- [Datasets :dvd:](#datasets-dvd)
  - [Human Anatomy :muscle:](#human-anatomy-muscle)
  - [Animal Anatomy :crocodile:](#animal-anatomy-crocodile)
  - [Balance :balance_scale:](#balance-balance_scale)
  - [Energetics :fire:](#energetics-fire)
  - [Walking :walking:](#walking-walking)
  - [Running :running:](#running-running)
  - [Instrumented Prostheses :chart_with_upwards_trend:](#instrumented-prostheses-chart_with_upwards_trend)
- [Gait Analysis and Motion Capture](#gait-analysis-and-motion-capture)
  - [Gait Analysis Markersets [TODO: add references and resources]](#gait-analysis-markersets-todo-add-references-and-resources)
  - [Motion Capture Data Import and Processing [WIP]](#motion-capture-data-import-and-processing-wip)
    - [Marker Trajectory Gap filling](#marker-trajectory-gap-filling)
    - [Inertial Measurement Units](#inertial-measurement-units)
- [Modelling and Simulation :computer:](#modelling-and-simulation-computer)
  - [Anthropometric Models](#anthropometric-models)
  - [Multibody and Physics Engines :sleeping::arrow_lower_left::apple:](#multibody-and-physics-engines-sleepingarrow_lower_leftapple)
  - [Computational Muscle Models](#computational-muscle-models)
  - [Neuromusculoskeletal Simulation Software :joystick:](#neuromusculoskeletal-simulation-software-joystick)
  - [Neuromusculoskeletal Simulation Tools](#neuromusculoskeletal-simulation-tools)
- [Subject-Specific Modelling](#subject-specific-modelling)
  - [Segmentation of Medical Images :art: [WIP]](#segmentation-of-medical-images-art-wip)
  - [Manipulation and Processing of Surface Meshes](#manipulation-and-processing-of-surface-meshes)
  - [Resources for Building Biomechanical Models from Medical Images](#resources-for-building-biomechanical-models-from-medical-images)
  - [Automatic Definition of Bony Landmarks and Reference Systems :skull:](#automatic-definition-of-bony-landmarks-and-reference-systems-skull)
  - [Uncertainty Quantification in Musculoskeletal Simulations [WIP]](#uncertainty-quantification-in-musculoskeletal-simulations-wip)
  - [Meshers of Surface Models](#meshers-of-surface-models)
  - [Statistical Shape Modelling [WIP]](#statistical-shape-modelling-wip)
- [Finite Element Analysis](#finite-element-analysis)
  - [Finite Element Analysis Software](#finite-element-analysis-software)
  - [Finite Element Analysis Software Tools](#finite-element-analysis-software-tools)
  - [Finite Element Models](#finite-element-models)
- [Statistical Analysis](#statistical-analysis)
- [Optimal Control and Trajectory Optimization :rocket: [WIP]](#optimal-control-and-trajectory-optimization-rocket-wip)
- [Societies and Initiatives :office:](#societies-and-initiatives-office)
- [Miscellaneous Online Resources](#miscellaneous-online-resources)
- [Contributing](#contributing)
- [License](#license)

## STILL TO ADD/CHECK
* Check AnyBody resource websites
* Database of simulations? (Some studies shared simulations, no raw data)
* Anatomical and gait data sets from MD-Paedigree (Montefiori et al.)
* Stanford Mobilize and mobile phone data
* visualization tools: [Paraview](https://www.paraview.org), Mayavi
* Winter's data from ISB/data in gait
* MuscleForceDirection in FE related (release github)
* anatomy dataset: https://www.cancerimagingarchive.net/access-data/
* https://github.com/mkjung99/biomechanics_dataset
* https://github.com/topics/biomechanics
* https://nda.nih.gov/oai
* https://github.com/facebookresearch/fairmotion
* https://github.com/bartbols/muscle_architecture_DTI
* http://hmc.csuohio.edu/projects/gait-control-id
* http://www.cloudcompare.org/
* MD-Paedigree simulations and geometries

## Online Courses :clapper:
* [Lectures on animal locomotion](https://mchenrylab.bio.uci.edu/e139) by Manny Azizi and Matt McHenry, UC Irvine (2020).
* [Lectures on optimal control](http://www.anilvrao.com/Optimal-Control-Videos.html) by Anil Rao (University of Florida).
* [Lectures on multibody dynamics](https://www.youtube.com/watch?v=1Tyxgv7RUdk&list=PLzAwokZEM7auZEBOJKNa_lCgz2rdgpYLL) by Jason Moore at UC Davis (2017).
* [KNES 789W - Advanced Projects in Kinesiology; Modeling & Simulation of Human Movement](https://www.youtube.com/watch?v=JXz5BHQBJhk&list=PLFNfmB3IG2Cf_0V5N9w_ZBKIHD2xg1H_g) by Ross Miller, University of Maryland (2020).
* [Neuromechanics course material](https://github.com/joshcash9/Neuromechanics_Course) by Joshua Cashaback (University of Delaware).
* [Neuromatch Academy](https://www.youtube.com/channel/UC4LoD4yNBuLKQwDOV6t-KPw): [the Neuromatch Academy](https://www.neuromatchacademy.org/) aims to introduce traditional and emerging tools of computational neuroscience to trainees.
* [Sport Biomechanics Lecture Series](https://www.youtube.com/channel/UCmG-bd1JL1ACP7hMzIUXwOg) curated by Stuart McErlain-Naylor. Includes introductory topics like  presentations of motion capture techniques by Vicon ([lecture 1](https://www.youtube.com/watch?v=1zJ14cW-JqY) and [lecture 2](https://www.youtube.com/watch?v=hM7xEoyP-4o)) and an [introduction](https://www.youtube.com/watch?v=2xgyTpsa14M#) of electromyography (EMG) by Delsys.

## YouTube Channels :tv:
* [AnyBody Technology Videos and Webcasts](https://www.youtube.com/channel/UCbgDnEKXyYOETR_Nb6YdehA)
* [American Society Biomechanics (ASB)](https://www.youtube.com/channel/UC0_WoykR3nSBrHAwyfLPzzw)
* [Biomch-V](https://www.youtube.com/channel/UCcv9iv6v4_l9dfDDW1PTZCA): includes videos from International Society of Biomechanics conferences.
* [European Society of Biomechanics (ESB)](https://www.youtube.com/channel/UCFkgDwfks-UkG7IDk8cBMMQ)
* [International Society of Biomechanics (tutorials and lectures)](https://isbweb.org/about-us/61-videos): It includes those recorded at the ISB congresses from 2007 and those provided by others.
* [International Society of Biomechanics in Sports (ISBS)](https://www.youtube.com/channel/UCYkzE6y_eKWa7KQOqZ6ZQUA/featured?disable_polymer=1): videos from ISBS2020 virtual conference.
* [Journal of Foot and Ankle Research](https://www.youtube.com/channel/UCuIdGMZMaDKRM7vyJ6Dbcwg)
* [OpenSim Videos and Webinars](https://www.youtube.com/user/OpenSimVideos/videos)
* [UCalgary Human Performance Lab](https://www.youtube.com/channel/UCxAOMJHF-5xQMFkLAutV7Dg/videos): videos from ISB/ASB2019 and Dynamic Walking 2019 conferences.
* [Manoj Srinivasan's channel](https://www.youtube.com/user/sjonam/videos)
* [Ross Miller's channel](https://www.youtube.com/channel/UCO_H7aZoIcwZiNc4KjiQQkg/videos) 
* [Stuart McErlain-Naylor channel](https://www.youtube.com/channel/UCmG-bd1JL1ACP7hMzIUXwOg)
* [NeuromechTV channel (content in english, portuguese, and spanish languages](https://www.youtube.com/neuromechTV)

## Videos :video_camera:
* [CNB-ASB Muscle Workshop](https://www.youtube.com/watch?v=Ur9wYYR0nac&feature=youtu.be): presentations on the topic `Integrative Muscle Modelling for Neuromechanics`.
* [A critique of Induced Acceleration Analysis](https://www.youtube.com/watch?v=2EmwIM_uQnk&t=18s) by Andy Ruina (WCB2014).
* [F8 2019 - VR Full Body Tracking & Avatars](https://www.youtube.com/watch?v=FhiAFo9U_sM) and [blog post](https://uploadvr.com/facebook-f8-2019-body-tracking/)
* [Running with bone pins](https://www.youtube.com/watch?v=nf6jkyNgkwE): video of data collection in subject running with bone pins shared by Ton Van den Bogert.
* [Introduction to Trajectory Optimization](https://www.youtube.com/watch?v=wlkRYMVUZTs) by [Matthew Kelly](http://www.matthewpeterkelly.com/index.html). Very clear introduction to the topic with MATLAB resources linked in the video description.
<!-- * https://www.goatstream.com/research/ -->

## Teaching Resources :triangular_ruler:
* [ASB Teaching Repository](http://asbteachingrepository.herokuapp.com/) by the American Society of Biomechanics. Does not require membership to access.
* [Kwon3d website](http://www.kwon3d.com/theory/prac.html): website with theory about most basic topics in biomechanics.
* [How to review a paper](https://www.sciencemag.org/careers/2016/09/how-review-paper) from Science Magazine.
* [Trajectory Optimization Toolbox](https://github.com/MatthewPeterKelly/OptimTraj) by Matthew Kelly, including some [excellent examples](https://github.com/MatthewPeterKelly/dscTutorials) and some [course materials](https://github.com/MatthewPeterKelly/ME149_Spring2018).
* [Notes on Scientific Computing for Biomechanics and Motor Control](https://github.com/BMClab/BMC) by Marcos Duarte and Renato Watanabe. A beautiful collection of lecture notes and code on scientific computing and data analysis for Biomechanics and Motor Control in the form of Jupyter notebooks (python).
* [Optimal Control Workshop](https://simtk.org/projects/ocworkshop/) by BJ Fregly. Files distributed at the NSF-funded Optimal Control Workshop held on July 9, 2015 at the University of Edinburgh as part of the XV International Symposium on Computer Simulation in Biomechanics.
* [OpenSim teaching Hub](https://simtk-confluence.stanford.edu/display/OpenSim/Teaching+Hub) by the OpenSim Team. Includes materials from the Neuromuscular Biomechanics Lab in the Department of Bioengineering at Stanford University. Does not require membership to access.
* [Tutorial: 3D Kinematics and Inverse Dynamics MATLAB scripts](https://uk.mathworks.com/matlabcentral/fileexchange/58021-3d-kinematics-and-inverse-dynamics?s_tid=prof_contriblnk) by Raphael Dumas, including some examples.
* [Tutorial: Musculoskeletal Model for Simulation of Walking](https://www.youtube.com/watch?v=Z4BoVVpju88) by Van den Bogert's tutorial (Dynamic Walking, 2011), including a section on computational muscle modelling and one on walking simulation using a 2D musculoskeletal model.
* [Tutorial: Kane’s Method for an inverted pendulum](https://figshare.com/articles/journal_contribution/Kane_pdf/7791647) by Ross Miller. A tutorial on Kane's Method for deriving equations of motion, demonstrated on an inverted pendulum.

## Books :blue_book:
* [Calculus made Easy](http://calculusmadeeasy.org) by Silvanus P. Thompson.
* [Dynamics: Theory and Applications](https://ecommons.cornell.edu/handle/1813/638) by Kane and Levinson.


## Datasets :dvd:

### Human Anatomy :muscle:

* **Visible Human Project**: public-domain library of cross-sectional cryosection, CT, and MRI images obtained from one male cadaver and one female cadaver. The dataset in NIfTI format, easier to import and use in segmentation software, were provided by Bart Bolsterlee (see further details [here](https://twitter.com/bartbolsterlee/status/1296594646898892800) and code for conversion [here](https://github.com/bartbols/VH2NIfTI)).      
:page_facing_up: [paper](https://doi.org/10.1109/5.662875) |
:dvd: [dataset](https://www.nlm.nih.gov/databases/download/vhp.html) |
:dvd: [dataset in NIfTI format](https://drive.google.com/drive/folders/1LBBIax6wpWBsiEcyXDrXNqyDSEB9rinO) |
:computer: [website](https://www.nlm.nih.gov/research/visible/visible_human.html) 
   
* **Visible Korean Human**: similar to the Visible Human Project but on Korean cadavers. Segmentated images are provided together with the section images.  
:page_facing_up: [paper](https://doi.org/10.1109/TMI.2004.842454) |
:dvd: [dataset](http://vkh.ajou.ac.kr/#vk) |
:computer: [website](http://vkh.ajou.ac.kr) (scroll down for English version)

* ~~**Chinese Visible Human**: similar to the Visible Human Project but on Chinese cadavers.~~ **the dataset does not seem to be available anymore**, despite being still listed on a [related website](https://appsrv.cse.cuhk.edu.hk/~vrcentre/index.html).  
:page_facing_up: [paper](https://dx.doi.org/10.1111%2Fj.0021-8782.2004.00274.x) |
:computer: [website](http://www.chinesevisiblehuman.com)

* **fastMRI dataset** by Facebook AI and NYU (2019-2020). Data from more than 1,500 fully sampled knee MRIs obtained on 3 and 1.5 Tesla magnets and DICOM images from 10,000 clinical knee MRIs also obtained at 3 or 1.5 Tesla. Includes also brain scans. **No segmentation available.**</br>
:page_facing_up: [paper](https://arxiv.org/abs/1811.08839?fbclid=IwAR1MuusEHDfRwQYb72OHKfdsL5F0OkCbdiI5wQsjJIQKMyAK-cao_wPYUN0)
:computer: [website](https://fastmri.org/dataset)
:star: [resources](https://github.com/facebookresearch/fastMRI/)

* **Development and validation of statistical shape models of the primary functional bone segments of the foot.** by Tamara Grant et al. (2019). Dataset includes manually segmented three-dimensional bone geometry models (.STL) from magnetic resonance images of 34 subjects of first metatarsal (29 geometries), midfoot (second-to-fifth metatarsals, cuneiforms, cuboid, and navicular) (33 geometries), calcaneus (27 geometries), and talus (34 geometries). **not all geometries are used**.
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3464747.svg)](https://doi.org/10.5281/zenodo.3464747)</br>
:page_facing_up: [paper](https://doi.org/10.7717/peerj.8397) |
:dvd: [dataset](https://zenodo.org/record/3464747#.X0P2qMhKgdU)

* **Are Subject-Specific Musculoskeletal Models Robust to the Uncertainties in Parameter Identification?** by  by Giordano Valente et al. (2014). Dataset includes MRI scans on a single healthy male participant and gait lab data of a single gait cycle.</br>
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0112625) |
:dvd: [dataset](https://simtk.org/projects/subspecmodeling)

* **MB Knee: Multibody Models of the Human Knee** by Trent Guess. The data set includes four knee models, one based on in vivo measurements from a 29 year old female and three based on cadaver knees that were physically tested in a dynamic knee simulator. Knee geometries (bone, cartilage, and mensici) were derived from Magnetic Resonance Imaging (MRI) and ligament insertions come from MRI, the literature, and probing the cadaver knees. The site also contains information on ligament modeling, such as bundle insertion locations and zero load lengths.  
:dvd: [dataset](https://simtk.org/projects/mb_knee)

* **OpenKnee** by Ahmet Erdemir. Open Knee(s) is aimed to provide free access to three-dimensional finite element representations of the knee joint. Dataset includes one knee specimen from the first generation of data collected and 21 specimens (knee id up to 22, missing one) for second generation.  
:page_facing_up: [paper 2016](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4876308/) |
:page_facing_up: [paper 2013](https://doi.org/10.1115/FMD2013-16033) |
:page_facing_up: [ASB abstract 2010](http://www.asbweb.org/conferences/2010/abstracts/181.pdf) |
:page_facing_up: [User's Guide 2010](https://simtk.org/websvn/wsvn/openknee/_gen1/doc/guide.pdf) |
:dvd: [dataset](https://simtk.org/projects/openknee)

* **Subject-specific muscle properties from diffusion tensor imaging significantly improve the accuracy of musculoskeletal models** by James Charles et al. (2020). Includes MRI scans (T1‐weighted anatomical turbo spin‐echo and diffusion tensor imaging) and Isokinetic and isometric torque measurement from 10 subjects (5 female). MRI images are segmented and processed to obtain muscle architecture.  
:page_facing_up: [paper](https://doi.org/10.1111/joa.13261) |
:dvd: [dataset](http://datacat.liverpool.ac.uk/1105/)

* **The Virtual Skeleton Database: An Open Access Repository for Biomedical Research and Collaboration** by Michael Kistler et al. (2013). Dataset including post mortem CT images of 50 subjects. **Despite several attempts I was never granted access to these data, although I know of others who did.**  
:page_facing_up: [paper](https://dx.doi.org/10.2196%2Fjmir.2930) |
:dvd: [dataset](https://www.smir.ch/objects/214315) |
:computer: [website](https://www.smir.ch/)
   * _SMIR pelves and selected pelvic landmarks_ from five experienced raters (20 pelves). ![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3384055.svg)</br>
   :page_facing_up: [paper](https://www.nature.com/articles/s41598-019-49573-4) |
   :dvd: [dataset](https://doi.org/10.5281/zenodo.3384055)
   * _SMIR pelves and femurs_ segmented bone from 20 CT scans available in MATLAB format.  
   :dvd: [dataset](https://github.com/RWTHmediTEC/VSDFullBodyBoneModels)
   
* **BodyParts3D** by Nobutaka Mitsuhashi et al. (2003). This is a 3D structure database for anatomical concepts that extends beyond biomechanics.  
:page_facing_up: [paper](https://doi.org/10.1093/nar/gkn613) |
:dvd: [dataset](http://lifesciencedb.jp/bp3d/) 

* **Femur and tibia surface mesh set** by Nolte et al. (2020). The data set contains bone geometries of the left and right thigh (femur) and shank (tibia and fibula) segmented from magnetic resonance (MR) scans of 35 healthy volunteers (22 male, 13 female). [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.167808.svg)](https://doi.org/10.5281/zenodo.167808)</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.gaitpost.2020.02.010) |
:dvd: [dataset](https://zenodo.org/record/167808#.X0O4kMhKgdV)

* **Natural Knee Data** by University of Denver Center for Orthopaedic Biomechanics. CT and MRI images are provided for 7 knee specimens (5 cadaveric subjects) plus solid models  created from the CT images. In addition, during dissection of the knees, surfaces and ligament insertions and origins were outlined on the bones and recorded as probed points.  
:dvd: [dataset](https://digitalcommons.du.edu/natural_knee_data) |
:computer: [website](https://simtk.org/projects/knee_model)

* **Living Biomechanics of the Knee** by University of Denver Center for Orthopaedic Biomechanics.  Kinematic and loading data from an experiment that used quadriceps force to extend the knee. The objective of this data was to provide a foundation to create a computer model representation of the patella joint in order to predict motion and forces across healthy and pathological specimens.
:dvd: [dataset](https://digitalcommons.du.edu/living_kinematics_knee/)
:computer: [website](https://simtk.org/projects/knee_model)

* **Twente Lower Extremity (TLEM) Dataset** by Martin Klein Horsman et al. (2007). Anatomical data intended for musculoskeletal modelling obtained by the dissection of a single male cadaver.  
:page_facing_up: [PhD thesis](https://research.utwente.nl/en/publications/the-twente-lower-extremity-model-consistent-dynamic-simulation-of)
:page_facing_up: [paper](https://doi.org/10.1016/j.clinbiomech.2006.10.003) |
:dvd: [dataset (paywalled)](https://ars.els-cdn.com/content/image/1-s2.0-S0268003306001896-mmc1.doc)

* **TLEM2.0: A New Complete and Consistent Musculoskeletal Geometry Dataset for Subject-Specific Modelling of the Lower Extremity** by Vincenzo Carbone and René Fluit et al. (2015. New comprehensive dataset of the musculoskeletal geometry of the lower extremity, which is based on medical imaging data and dissection performed on the right lower extremity of a fresh male cadaver. A complete cadaver dissection was performed, in which bony landmarks, attachments sites and lines-of-action of 55 muscle actuators and 12 ligaments, bony wrapping surfaces, and joint geometry were measured.  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2014.12.034) |
:dvd: [dataset - requires registration](https://tlemsafe.eu/) |
:computer: [website](https://tlemsafe.eu/)

* **Shoulder morphological data** by the Dutch Shoulder Group. Includes data from several studies performed in 1988-2002 period.  
:dvd: [dataset](http://homepage.tudelft.nl/g6u61/repository/shoulder/overview.htm)

* **Hand and Wrist Dataset** by Goislard de Monsabert et al. (2018). Data set intended for modelling including the musculoskeletal geometry and muscle morphology from the elbow to the finger tips. Clinical imaging, optical motion capture and microscopy were used to create a dataset from a single specimen.  
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10439-017-1936-z#SecESM1) |
:dvd: [dataset](https://static-content.springer.com/esm/art%3A10.1007%2Fs10439-017-1936-z/MediaObjects/10439_2017_1936_MOESM1_ESM.pdf)

* **Muscle Modelling Database** by Ross Miller (2018). A summary of muscle mechanical parameters in the human lower limb from the anatomy, muscle/exercise physiology, and biomechanics literature for use in Hill-based muscle model.  
:page_facing_up: [paper](https://link.springer.com/referenceworkentry/10.1007%2F978-3-319-30808-1_203-2) |
:dvd: [dataset](https://figshare.com/articles/dataset/Muscle_model_parameters/4275854)

<!--* **Cal Poly Human Motion Biomechanics Lab Knee Joint Finite Element Model** https://simtk.org/projects/cphmbkneefem/ -->

### Animal Anatomy :crocodile:

* **CT scans of various animals** from John Hutchinson's group.  
:dvd: [dataset](https://osf.io/4sc96/)

* **New Mexico Decedent Image Database (NMDID)**: provides researchers with access to whole human body computed tomography (CT) scans and a rich body of associated metadata.   
:computer: [website](https://nmdid.unm.edu/welcome)

* **Digital Morphology Museum of Kyoto University (KUPRI)**: DMM provides a large collection of CT and MRI tomography scans of various primates.   :computer: [website](http://dmm.pri.kyoto-u.ac.jp/dmm/WebGallery/index.html)

* **DigiMorph**: Digital Morphology library is a dynamic archive of information on digital morphology and high-resolution X-ray computed tomography of biological specimens.  
:computer: [website](http://digimorph.org)

* **The Open Research Scan Archive (formerly: Penn Cranial CT Database)** contains high resolution (sub-millimeter) scans of human and non-human crania from the Penn University Museum and other institutions.   
:computer: [website](https://penn.museum/sites/orsa/Overview.html)

* **Phenome10K**: A free online repository for 3-D scans of biological and palaeontological specimens.  
:computer: [website](https://phenome10k.org)

* **MorphoMuseuM (M3)**: is a peer reviewed, online journal that publishes 3D models of vertebrates, including models of type specimens, anatomy atlases, reconstruction of deformed or damaged specimens, and 3D datasets. 
:computer: [website](https://morphomuseum.com/collections)

* **Morphosource** by Duke University. MorphoSource has approximately 27,000 published 3D models of biological specimens (largely skeletal material). You can view all of these in your web browser with no required software. Around 13,000 of these are open access and can be freely downloaded for further visualization or measurement.  
:computer: [website](https://www.morphosource.org)


### Balance :balance_scale:

* **BDS: A public data set of human balance evaluations**  by Damiana dos Santos and Marco Duarte (2016).  
:page_facing_up: [paper](https://peerj.com/articles/2648/) |
:dvd: [dataset](https://figshare.com/articles/A_public_data_set_of_quantitative_and_qualitative_evaluations_of_human_balance/3394432) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/bds/) |
:star: [resources](https://github.com/BMClab/datasets/tree/master/BDS)

* **PDS: A data set with kinematic and ground reaction forces of human balance** by Damiana dos Santos et al. (2017).  
:page_facing_up: [paper](https://peerj.com/articles/3626/) |
:dvd: [dataset](https://figshare.com/articles/A_data_set_with_kinematic_and_ground_reaction_forces_of_human_balance/4525082) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/pds/)

### Energetics :fire:

* **ISB2019 Metabolic cost session_: Data for participants in ISB2019 session on model-based prediction of the metabolic cost of human locomotion.** by Ross Miller (2019).    
:page_facing_up: [users' guide](https://figshare.com/articles/journal_contribution/User_Guide/7086770)
:dvd: [dataset](https://figshare.com/projects/ISB2019_Metabolic_cost_session/38738)

* **Dataset for Metabolic Cost Calculations of Gait using Musculoskeletal Energy Models, a Comparison Study** by Anne D. Koelewijn et al. (2019). The data set contains raw and processed data of gait analysis experiments of level and inclined walking at two speeds for 12 participants. The slopes were uphill and downhill with 8% incline. The raw data contains the output of the force plates and marker data, as well as raw measurements from an K4B2 system. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1973799.svg)](https://doi.org/10.5281/zenodo.1973799)  
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0222037) |
:dvd: [dataset](https://zenodo.org/record/1973799#.X0PtVshKgdU)


### Walking :walking:

* **A database of human gait performance on irregular and uneven surfaces collected by wearable sensors** by Luo et al. (2020). Data from Inertial Measurement Units (IMU) from thirty participants (fifteen males and fifteen females, 23.5 ± 4.2 years, 169.3 ± 21.5 cm, 70.9 ± 13.9 kg) who wore six IMUs while walking on nine outdoor surfaces with self-selected speed (16.4 ± 4.2 seconds per trial). Intended for machine learning purposes.</br>
:page_facing_up: [paper](https://www.nature.com/articles/s41597-020-0563-y) |
:dvd: [dataset](https://doi.org/10.6084/m9.figshare.c.4892463) |
:dvd: [metadata](https://springernature.figshare.com/articles/Metadata_record_for_A_database_of_human_gait_performance_on_irregular_and_uneven_surfaces_collected_by_wearable_sensors/12505022) |
:star: [resources](https://github.com/UF-ISE-HSE/UnevenWalkingSurface)

* **An Open Data Set of Inertial, Magnetic, Foot–Ground Contact, and Electromyographic Signals From Wearable Sensors During Walking.** by Miraldo DC, Watanabe RN and Duarte M (2020).  Data were acquired from 22 healthy adults using wearable sensors and walking at self-selected comfortable, fast and slow speeds, and standing still. In total, there are data of 9,661 gait strides. The dataset includes gait events and notebooks exemplifying how to access and visualize the data.  
:page_facing_up: [paper](https://doi.org/10.1123/mc.2020-0023) |
:dvd: [dataset](https://figshare.com/articles/Dataset_of_gait_and_inertial_sensors/7778255) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/geds/) |
:star: [resources](https://github.com/BMClab/datasets/tree/master/GEDS)

* **A multimodal dataset of human gait at different walking speeds established on injury-free adult participants** by Céline Schreiber & Florent Moissenet (2019). Dataset collected on 50 healthy and injury-free adults, with no lower and upper extremity surgery in the last two years. Participants walked at 5 speeds during one unique session. Three dimensional trajectories of 52 reflective markers spread over the whole body, 3D ground reaction forces and moment, and electromyographic signals were simultaneously recorded.  
:page_facing_up: [paper](https://www.nature.com/articles/s41597-019-0124-4) 
:dvd: [dataset](https://doi.org/10.6084/m9.figshare.7734767)

* **A public data set of overground and treadmill walking kinematics and kinetics of healthy individuals** by Claudiane A. Fukuchi et al. (2018). Dataset of 42 healthy volunteers (24 young adults and 18 older adults) who walked both overground and on a treadmill at a range of gait speeds.  
:page_facing_up: [paper](https://peerj.com/articles/4640) |
:dvd: [dataset](https://figshare.com/articles/dataset/A_public_data_set_of_overground_and_treadmill_walking_kinematics_and_kinetics_of_healthy_individuals/5722711/4) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/wbds/)

* **An elaborate data set on human gait and the effect of mechanical perturbations** by Jason Moore et al. (2015). Gait data set collected from fifteen subjects walking at three speeds on an instrumented treadmill. Each trial consists of 120 s of normal walking and 480 s of walking while being longitudinally perturbed during each stance phase with pseudo-random fluctuations in the speed of the treadmill belt.  
:page_facing_up: [paper](https://doi.org/10.7717/peerj.918) |
:dvd: [dataset](https://zenodo.org/record/13030#.Xz1FeehKgdU) |
:computer: [resources](https://github.com/csu-hmc/perturbed-data-paper) 

* **Multiple Speed Walking Simulations** by May Liu et al. (2008). Data set with eight subjects (two males) walking overground at very slow, slow, free, and fast speeds.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2008.07.031) |
:dvd: [dataset](https://simtk.org/projects/mspeedwalksims) 

* **Normative gait data** from Chris Kirtley's [website](http://www.clinicalgaitanalysis.com/) on clinical gait analysis. **Website does not seem maintained.**  
:computer: [website](http://www.clinicalgaitanalysis.com/data/) 


### Running :running:

* **A public data set of running biomechanics and the effects of running speed on lower extremity kinematics and kinetics** by Reginaldo K. Fukuchi et al. (2017). The lower-extremity kinematics and kinetics data of 28 regular runners were collected using a three-dimensional (3D) motion-capture system and an instrumented treadmill while the subjects ran at 2.5 m/s, 3.5 m/s, and 4.5 m/s wearing standard neutral shoes.  
:page_facing_up: [paper](https://peerj.com/articles/3298) |
:dvd: [dataset](https://figshare.com/articles/A_comprehensive_public_data_set_of_running_biomechanics_and_the_effects_of_running_speed_on_lower_extremity_kinematics_and_kinetics/4543435/4) |
:computer: [website](http://pesquisa.ufabc.edu.br/bmclab/datasets/rbds/)

* **Ground reaction force metrics are not strongly correlated with tibial bone load when running across speeds and slopes: implications for science, sport and wearable tech**  by Emily Matijevich et al. (2019). Includes ten healthy individuals that performed running trials while GRFs and kinematics were collected. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3460691.svg)](https://doi.org/10.5281/zenodo.3460691)    
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0210000) |
:dvd: [dataset and resources](https://zenodo.org/record/3460691#.Xz-1tuhKgdU)

* **Muscle contributions to mass center accelerations over a range of running speeds** by Samuel Hamner and Scott Delp (2013). Repository of experimental data (i.e., motion capture, EMG, GRFs), subject-specific models, and muscle-driven simulation results of 10 male subject running across a range of speeds: 2 m/s, 3 m/s, 4 m/s, and 5 m/s.   
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2012.11.024) |
:dvd: [dataset](https://simtk.org/projects/nmbl_running/)

* **Simulated muscle fiber lengths and velocities during walking and running** by Edith Arnold et al. (2013). Models and results for simulations of muscle fiber dynamics for five subjects walking at four speeds and running at four speeds. **The subject numbers are noncontiguous to maintain alignment with the related project: https://simtk.org/projects/nmbl_running**.  
:page_facing_up: [paper](https://jeb.biologists.org/content/216/11/2150) |
:dvd: [dataset](https://simtk.org/projects/muscfib_walkrun)

* **Muscle function of overground running across a range of speeds** by Tim Dorne et al. (2012). Running data and musculoskeletal models for a single representative subject (JA1). Actual running speeds: 3.56 m/s, 5.20 m/s, 7.00 m/s and 9.49 m/s.  
:page_facing_up: [paper](https://doi.org/10.1242/jeb.064527) |
:dvd: [dataset](https://simtk.org/projects/runningspeeds)

### Instrumented Prostheses :chart_with_upwards_trend:

* **Grand Challenge Competition to Predict In Vivo Knee Loads** By BJ Fregly et al. (2012). Data sets from instrumented knee prostheses used in the "Grand Challenge Competition". Data include medical images and segmentations (for most participants), tibial contact force, video motion, ground reaction, muscle EMG, muscle strength, static and dynamic imaging, and implant geometry data for six patients. This is the most completely and easily accessible dataset of measurements from instrumented prostheses.   
:page_facing_up: [paper1](https://doi.org/10.1002/jor.22023) |
:page_facing_up: [paper2](https://doi.org/10.1115/1.4023255) |
:dvd: [dataset](https://simtk.org/projects/kneeloads)

* **Orthoload** by the Julius Wolff Institute of the Charité in Berlin. This online dataset includes loads occuring in human joints measured directly in patients by using instrumented hip, knee, shoulder and spinal implants. OrthoLoad supplies numerical load data and videos, which contain load-time diagrams and synchronous images of the subject’s activities. **No joint kinematics available outside `larger cooperative projects`, except few sample data:**.  
:page_facing_up: [publication list](https://orthoload.com/publications/) |
:dvd: [dataset hip](http://www.wiki.orthoload.com/index.php?title=Hip_joint_III) |
:dvd: [dataset knee](http://www.wiki.orthoload.com/index.php?title=Knee_joint) |
:dvd: [dataset shoulder](http://www.wiki.orthoload.com/index.php?title=Shoulder_joint) |
:dvd: [dataset spine](http://www.wiki.orthoload.com/index.php?title=Vertebral_body_replacement) |
:dvd: [sample comprehensive](https://orthoload.com/comprehensive-data-sample) |
:computer: [website](https://orthoload.com/)

* **HIP98** by Georg Bergmann et al. (1998). The data collection CD-ROM HIP98 contains the forces acting in the hip joint during the most common activities of daily living. Measurements were taken 1998 in 4 subjects (implant loads, synchronous videos, gait analysis data, calculated muscle forces, EMG signals and numbers for the frequencies of the different activities).The loads acting in a ’typical’ or representative subject are also provided. **Issues in installing the database in recent Microsoft operative systems. The data will be extracted but the GUI will not work.**  
:page_facing_up: [paper](https://doi.org/10.1016/s0021-9290(01)00040-9) |
:dvd: [dataset](https://orthoload.com/wp-content/uploads/hip98.zip) |
:computer: [website](https://orthoload.com/test-loads/data-collection-hip98)

* **CAMS-KNEE** by William Taylor et al. (2017). Datasets collected on a cohort of 6 subjects with instrumented knee implants (Charité – Universitätsmedizin Berlin) synchronized with a moving fluoroscope (ETH Zürich) and other measurement techniques (whole body kinematics, ground reaction forces, video data, and electromyography data) for multiple complete cycles of 5 activities of daily living. **Data must be requested submitting a project description.** I was NOT granted access to the entire data set for exploring the dataset.  
**Link to live dataset is broken.**  </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2017.09.022) |
:cd: [data request](https://cams-knee.orthoload.com/data/data-request/) |
:cd: [live dataset (CAMS-KNEE workshop)](https://cams-knee.orthoload.com/workshop-data/) |
:computer: [website](https://cams-knee.orthoload.com/)

## Gait Analysis and Motion Capture

### Gait Analysis Markersets [TODO: add references and resources]

* CAST
* IORGait
* LAMB
* SAFLo
* T3Dg

### Motion Capture Data Import and Processing [WIP]

* [c3dserver](https://www.c3dserver.com/) C++/MATLAB)

* [ezc3d](https://github.com/pyomeca/ezc3d) (C++/MATLAB/Python)

* [BTK - Biomechanical ToolKit](http://biomechanical-toolkit.github.io/) (C++/MATLAB/Python)

* [MOKKA](https://biomechanical-toolkit.github.io/mokka/): GUI built on BTK functionalities. 
Allows visualisation of c3d contents and basic processing, such as filtering and event detection. Great open source alternative to Vicon Nexus for these functionalities.

* **motoNMS** by Alice Mantoan et al. (2015). MATLAB tool that provides a complete, user friendly and highly configurable tool to automatically process experimental motion data from different laboratories in C3D format for their use into the OpenSim neuromusculoskeletal software. </br>
:page_facing_up: [paper](https://link.springer.com/article/10.1186/s13029-015-0044-4)
:computer: [website](https://simtk.org/projects/motonms)
:floppy_disk: [source](https://github.com/RehabEngGroup/MOtoNMS)

* **BiomechZoo** by Philippe C Dixon. BiomechZoo is a user-customizable toolbox for the analysis of biomechanical data within the MatLab programming environment. Please take a look at the Wiki for setup information and user instructions.  
:computer: [website](https://www.biomechzoo.com)
:floppy_disk: [source](https://github.com/PhilD001/biomechZoo)

* **The CGM 2.i Project** by Fabian Leboeuf et al. (2019). Python :snake: implementation of an evolved conventional gait model.  
:page_facing_up: [paper](https://doi.org/10.1016/j.gaitpost.2019.01.034) |
:computer: [website](https://pycgm2.github.io/) |
:floppy_disk: [source](https://github.com/pyCGM2/pyCGM2)

* **Pyomeca** by the [S2M Lab](https://www.facebook.com/s2mlab/). Pyomeca is a Python :snake: library allowing you to carry out a complete biomechanical analysis; in a simple, logical and concise way. It enables extraction, processing and visualization of biomechanical data for use in research and education.</br> 
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.02431)
:computer: [website](https://pyomeca.github.io/)
:floppy_disk: [source](https://github.com/pyomeca/pyomeca)

#### Marker Trajectory Gap filling

* **Automated Gap Filling and Tools for Motion Capture** by the Sensor-Fusion team from EPIC lab @GeorgiaTech. Gap filling is based on inverse kinematics approach.
:page_facing_up: [paper](https://doi.org/10.1080/10255842.2020.1789971) |
:computer: [website](https://simtk.org/projects/opensense)
:floppy_disk: [source](https://github.com/JonathanCamargo/MoCapTools)

* **MoGapFill** implemented by Fabian Leboeuf (Python :snake:). Low dimensional Kalman smoother that fills gaps in motion capture marker trajectories based on Burke and Lasenby 2016 paper.  
:page_facing_up: [Burke's paper 2016](http://dx.doi.org/10.1016/j.jbiomech.2016.04.016) |
:floppy_disk: [source](https://github.com/pyCGM2/MoGapFill)

#### Inertial Measurement Units

* **GaitPy** by Matthew Czech. Read and process raw vertical accelerometry data from a sensor on the lower back during gait; calculate clinical gait characteristics.  
:computer: [website](https://pypi.org/project/gaitpy/) |
:floppy_disk: [source](https://github.com/matt002/GaitPy)

* **OpenSense** TODO add description  
:page_facing_up: [documentation and examples](https://simtk-confluence.stanford.edu:8443/display/OpenSim/OpenSense+-+Kinematics+with+IMU+Data)
:computer: [website](https://simtk.org/projects/opensense)
:floppy_disk: [source](https://github.com/opensim-org/opensim-core)


## Modelling and Simulation :computer:

### Anthropometric Models

* **Repository of body segment parameter models** by Will Robertson. Contains the raw data for a multitude of body segment parameter models (see repository for list).  
:computer: [website](http://wspr.io/body-segment-param/) |
:floppy_disk: [source](https://github.com/wspr/body-segment-param)

* **Yeadon's model** by Chris Dembia et al. (2015). The human inertia model developed by Fred Yeadon in 1990.  
:page_facing_up: [paper](https://dx.doi.org/10.12688%2Ff1000research.5292.2) |
:floppy_disk: [source](https://github.com/chrisdembia/yeadon)

* **Hatze's model** by Will Robertson. A Matlab implementation of Hatze's 1980 anthropometric body segment parameter model.  
:page_facing_up: [Hatze's paper](https://doi.org/10.1016/0021-9290(80)90171-2) |
:floppy_disk: [source](https://github.com/wspr/hatze-biomech)


### Multibody and Physics Engines :sleeping::arrow_lower_left::apple:

* **Bullet Physics** by Erwin Coumans and Yunfei Bai (2016). Real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc.   
:page_facing_up: [Quick Start Guide](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.2ye70wns7io3) |
:computer: [website](https://pybullet.org/wordpress/) |
:floppy_disk: [source](https://github.com/bulletphysics/bullet3)

* **Drake** :dragon: by Russ Tedrake and the Drake Development Team (2019). C++ toolbox for analyzing the dynamics of our robots and building control systems for them, with a heavy emphasis on optimization-based design/analysis. Core development is now led by the Toyota Research Institute.  
:computer: [website](https://drake.mit.edu/) |
:floppy_disk: [source](https://github.com/RobotLocomotion/drake)

* **MuJoCo** by Emo Todorov for Roboti LLC. Initially it was used at the Movement Control Laboratory, University of Washington. MuJoCo is a  commercial physics engine aiming to facilitate research and development in robotics, biomechanics, graphics and animation, and other areas where fast and accurate simulation is needed.  
:computer: [website](http://www.mujoco.org) |
:star: [plugin for importing OpenSim models](https://github.com/aikkala/O2MConverter)

* **ODE (Open Dynamics Engine)** by Russell L. Smith. Open source, high performance library for simulating rigid body dynamics. It is fully featured, stable, mature and platform independent with an easy to use C/C++ API. It has advanced joint types and integrated collision detection with friction. ODE is useful for simulating vehicles, objects in virtual reality environments and virtual creatures. It is currently used in many computer games, 3D authoring tools and simulation tools.  
:computer: [website](https://www.ode.org) |
:floppy_disk: [source](https://bitbucket.org/odedevs/ode/src/master)

* **Pinocchio** by Carpentier et al. (2019). Pinocchio is an open-source library (C++ with Python :snake: bindings) for efficiently computing the dynamics (and derivatives) of articulated rigid-body models (robot, avatars, skeletal models, etc.). It implements algorithms following the methods described in Featherstone's 2008 [book](https://www.springer.com/gp/book/9780387743141), and their derivatives.  
:page_facing_up: [paper](https://hal.archives-ouvertes.fr/hal-01866228) |
:computer: [website](https://gepettoweb.laas.fr/doc/stack-of-tasks/pinocchio/master/doxygen-html/) |
:floppy_disk: [source](https://github.com/stack-of-tasks/pinocchio)

* **PyDy** by Jason Moore. A tool kit written in the Python programming language that utilizes an array of scientific programs to enable the study of multibody dynamics.  
:page_facing_up: [paper](http://dx.doi.org/10.1115/DETC2013-13470) |
:floppy_disk: [source](https://rbdl.github.io) |
:star: [Human Standing Tutorial](https://github.com/pydy/pydy-tutorial-human-standing) |
:movie_camera: [YouTube tutorials](https://www.youtube.com/watch?v=r4piIKV4sDw)

* **RBDL (Rigid Body Dynamics Library)** by Martin L. Felis (Heidelberg University). A multibody engine heavily inspired by the pseudo code of the book "Rigid Body Dynamics Algorithms" of [Roy Featherstone](http://royfeatherstone.org/).  
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10514-016-9574-0) |
:computer: [website](https://rbdl.github.io/) |
:floppy_disk: [source](https://github.com/rbdl/rbdl)

* **SimBody** by Michael Sherman et al. (2011). Simboby is an open source, extensible, high performance toolkit including a multibody mechanics library aimed at the needs of biomedical researchers working in a variety of fields including neuromuscular, prosthetic, and biomolecular simulation.   
:page_facing_up: [paper](https://www.sciencedirect.com/science/article/pii/S2210983811000241) |
:computer: [website](https://simtk.org/projects/simbody) |
:floppy_disk: [source](https://github.com/simbody)

### Computational Muscle Models

* **Flexing Computational Muscle: Modeling and Simulation of Musculotendon Dynamics** by Matthew Millard et al. (2013). Source code and benchmarks to compare computational speed and physiological accuracy of several muscle models in OpenSim. </br>
:page_facing_up: [paper](https://doi.org/10.1115/1.4023390) |
:floppy_disk: [source](https://simtk.org/projects/opensim_muscle) |
:floppy_disk: [Matlab version](https://github.com/mjhmilla/Millard2012EquilibriumMuscleMatlabPort) |
:video_camera: [Webinar](https://www.youtube.com/watch?v=Q1rId1fOkjw)

* **MyoSim** by the [Campbell Lab](https://sites.google.com/g.uky.edu/campbellmusclelab). MyoSim is an open source computer software for modeling the mechanical properties (force, shortening, power output) of striated muscles. The software models the behavior of half-sarcomeres by extending Huxley-based cross-bridge distribution techniques with Ca2+ activation and cooperative effects. MyoSim can also simulate arbitrary cross-bridge schemes set by the researcher.</br>
:page_facing_up: [paper](https://rupress.org/jgp/article/143/3/387/43232/Dynamic-coupling-of-regulated-binding-sites-and) |
[:computer: webpage | :floppy_disk: source | :page_facing_up: documentation](http://myosim.campbellmusclelab.org/home)

* **Virtual Muscle** by Chen et al. (2000). Virtual Muscle provides a framework for constructing accurate muscle models that can be incorporated easily into complete
neuromusculoskeletal systems. The muscle model includes motor nuclei that accept a single command input (e.g. net synaptic drive or EMG envelope) and apportion it into recruitment and frequency modulation of subgroups of motor units with type-specific properties, type-specific contractile elements that produce force as a function of firing frequency, length and velocity, passive elastic elements for passive muscle force, passive elastic elements for series-compliance of tendons and aponeuroses. </br> 
:page_facing_up: [paper](http://e.guigon.free.fr/rsc/article/ChengEJEtAl00.pdf) |
:floppy_disk: [source](https://1otylmrj2pd20xsmv2kci0wn-wpengine.netdna-ssl.com/wp-content/uploads/2017/11/VM-4.0.1.zip) |
:page_facing_up: [Manual](https://1otylmrj2pd20xsmv2kci0wn-wpengine.netdna-ssl.com/wp-content/uploads/2017/11/VM-4.0.1-Users-Manual.pdf)

* **Volume Invariant Position-based Elastic Rods (VIPER)** by Baptiste Angles et al. (2019). VIPER is a modified formulation of position-based rods to include elastic volumetric deformations. Rods can provide a compact alternative to tetrahedral meshes for the representation of complex muscle deformations, as well as providing a convenient representation for collision detection. Muscles can be modelled as a bundle of rods, for which a technique to automatically convert a muscle surface mesh into a rods-bundle is also presented. The method can run in real time.</br>
:page_facing_up: [paper](https://dl.acm.org/doi/10.1145/3340260) |
:floppy_disk: [source](https://github.com/vcg-uvic/viper) |
:video_camera: [video](https://www.youtube.com/watch?v=2CGRfJJEu38)

### Neuromusculoskeletal Simulation Software :joystick:

* **The AnyBody Modeling System** by AnyBody Technology. Commercial software for musculoskeletal modelling and simulation.  
:page_facing_up: [paper](https://doi.org/10.1016/j.simpat.2006.09.001) |
:computer: [website](http://www.anybodytech.com) |
:star: [model repository](http://www.anybodytech.com/software/model-repository-ammr)

* **AnimatLab** - neuromechanical and neurorobotic simulator for building the body of a robot or biolgical organism in a physically accurate 3-D virtual world, and then layout a biologically realistic nervous system to control the animats behavior.   
:page_facing_up: [paper](https://www.sciencedirect.com/science/article/pii/S0165027010000087) |
:computer: [website](http://animatlab.com) |
:floppy_disk: [source](https://github.com/NeuroRoboticTech/AnimatLabPublicSource)

* **Artisynth** by John Lloyd et al. Artisynth is a 3D mechanical modeling system implemented in Java that supports the combined simulation of multibody and finite element models (linear and nonlinear materials), together with contact and constraints. </br> 
:page_facing_up: [paper](https://link.springer.com/chapter/10.1007/8415_2012_126) |
:page_facing_up: [paper-downloadable](https://www.cs.usask.ca/faculty/stavness/papers/lloyd2012-artisynth-a-fast-interactive-biomechanical-modeling-toolkit.pdf) |
:computer: [website](https://www.artisynth.org/Main/HomePage) |
:floppy_disk: [source](https://github.com/artisynth/artisynth_core)

* **Biomechanics of Bodies** - biomechanical modelling package implemented in MATLAB that contains a human musculoskeletal model and enables biomechanical and musculoskeletal calculations.   
:page_facing_up: [paper](https://pure.coventry.ac.uk/ws/portalfiles/portal/22762734/Shippen_et_al_BoB_Biomechanics_MATLAB.pdf) |
:computer: [website](https://www.bob-biomechanics.com)

* **GaitSym** by William Sellers (2014). Software for simulation of human and animal musculoskeletal biomechanics.  
:page_facing_up: [Config Reference Manual](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.705.9682&rep=rep1&type=pdf) |
:computer: [Animal Simulation Laboratory website](https://www.animalsimulation.org/) |
:floppy_disk: [source](https://github.com/wol101/GaitSym_2017)

* **MSMS Software for VR Simulations of Neural Prostheses and Patient Training and Rehabilitation** by Rahman Davoodi and Gerald E. Loeb. MSMS is a software for modeling of paralyzed and prosthetic limbs and simulation of their movement under various neural control strategies. The simulations of MSMS models can be run in typical PCs to test and evaluate different prosthetic control strategies or in real-time PCs with stereoscopic displays to enable design engineers and prospective users to evaluate candidate neural prosthetic systems and learn to operate them before actually receiving them.</br>
:page_facing_up: [paper](https://viterbi.usc.edu/pdfs/gloeb/95737.pdf) |
:computer: [website](https://bme.usc.edu/msms-software-downloads/)

* **OpenSim** by the National Center for Simulation in Rehabilitation Research, Stanford University. Open source software for biomechanical analysis and neuromusculoskeletal simulations.   
:page_facing_up: [paper2007](https://ieeexplore.ieee.org/document/4352056) |
:page_facing_up: [paper2019](https://doi.org/10.1371/journal.pcbi.1006223) |
:computer: [website](https://opensim.stanford.edu) |
:computer: [binaries](https://simtk.org/projects/opensim) |
:floppy_disk: [source](https://github.com/opensim-org/opensim-core)

* **SCONE** by Thomas Geijtenbeek. Open source software for predictive simulation of biological motion. It generates actuator patterns and motion trajectories that optimally perform a specific task, according to high-level objectives such as walking speed, pain avoidance, and energy efficiency.   
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.01421) |
:computer: [website](https://scone.software/doku.php) |
:computer: [binaries](https://simtk.org/projects/scone) |
:floppy_disk: [source](https://github.com/opensim-org/SCONE)

### Neuromusculoskeletal Simulation Tools 

* **Batch OpenSim Processing Scripts (BOPS)** by Alice Mantoan et al. (2020). MATLAB based, user friendly and easy-to-use tool to perform batch process of the most commonly used OpenSim Tools (IK, ID, MA, SO and JRA).</br>
:computer: [website](https://simtk.org/projects/bops ) |
:floppy_disk: [source](https://github.com/RehabEngGroup/BOPS)

* **OpenSim JAM: A framework to simulate Joint and Articular Mechanics in OpenSim** by Colin Smith (2020). OpenSim JAM is a collection of force component plugins, models, and executables (tools) that are designed to enable OpenSim musculoskeletal simulations that include detailed joint mechanics. The project extends the opensim-core capabilities to enable joint representations that include 6 degree of freedom (DOF) joints (without kinematic constraints) and explicit representations of articular contact and ligament structures.  
:page_facing_up: [reference papers for each component](https://github.com/clnsmith/opensim-jam/tree/master/opensim-jam-release) |
:computer: [website and binaries](https://simtk.org/projects/opensim-jam) |
:floppy_disk: [source](https://github.com/clnsmith/opensim-jam)

* **CEINMS: Calibrated EMG-Informed Neuromusculoskeletal Modelling Toolbox** by Claudio Pizzolato et al. (2015). OpenSim toolbox that implements various techniques for running musculoskeletal simulations from experimental measurements of electromyography (EMG). See CEINMS paper for list and examples.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2015.09.021)
:computer: [website](https://simtk.org/projects/ceinms) |
:floppy_disk: [source](https://github.com/CEINMS/CEINMS)

* **OpenSim Marker Placement Toolbox** by Mark Price. An OpenSim toolbox implementing a motion capture marker placement refinement algorithm based on minimizing inverse kinematics tracking errors. </br>
:page_facing_up: [paper](https://doi.org/10.1002/cnm.3283) |
:floppy_disk: [source](https://github.com/UMass-OpenSim/opensim-marker-place-toolbox)

* **CusToM: a Matlab toolbox for musculoskeletal simulation** by Antoine Muller (2019). The Customizable Toolbox for Musculoskeletal simulation (CusToM)  is a MATLAB toolbox aimed at performing inverse dynamics based musculoskeletal analyzes. It can perform inverse kinematics, inverse dynamics, prediction of ground reaction forces and muscle forces, compute kinematics from inertial measurement units, etc.</br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.00927) |
:floppy_disk: [source](https://github.com/anmuller/CusToM) |
:star: [workshop materials](https://github.com/cpontonn/CusToM-Workshop)

* **FreeBody** by the Daniel Cleather and Anthony Bull, MSk Dynamics group, Imperial College London. FreeBody is a segment-based musculoskeletal model of the lower limb implementing TLEM anatomical dataset. FreeBody is a fully-open source Windows application and Matlab code that may be used as given or as a framework for the development of your own bespoke models.</br>
:page_facing_up: [paper](https://doi.org/10.1098/rsos.140449) |
:computer: [website](https://www.msksoftware.org.uk/software/freebody/)

* **Geyer's 2010 neuromuscular model** by Hermut Geyer (2010). Simulink implementation of a neuromusculoskeletal model used in walking simulation with stretch reflexes.</br>
:page_facing_up: [paper](https://www.cs.cmu.edu/~hgeyer/Publications/Geyer&Herr-ReflexModel2Column.pdf) |
:floppy_disk: [source](https://www.cs.cmu.edu/~hgeyer/Software/Neuromuscular%20Model/Geyer%20Neuromuscular%20Model.zip) 

* **Modeling musculoskeletal kinematic and dynamic redundancy using null space projection** by Dimitar Stanev and Konstantinos Moustakas (2019). Python :snake: methods for modeling, simulation and analysis of redundant musculoskeletal systems based on muscle space projection on segmental level reflexes and the computation of the feasible muscle forces for arbitrary movements. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2000421.svg)](https://doi.org/10.5281/zenodo.2000421)  
:page_facing_up: [paper](https://doi.org/10.1371/journal.pone.0209171) |
:computer: [website](https://simtk.org/projects/redundancy)
:floppy_disk: [source](https://github.com/mitkof6/musculoskeletal-redundancy)

* **Stiffness modulation of redundant musculoskeletal systems** by Dimitar Stanev and Konstantinos Moustakas (2019). Python tool :snake: implementing an approach that explores the entire space of possible solutions of the muscle redundancy problem using the notion of null space and rigorously accounts for the effect of muscle redundancy in the computation of the feasible stiffness characteristics. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2575332.svg)](https://doi.org/10.5281/zenodo.2575332)  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2019.01.017) |
:computer: [website](https://simtk.org/projects/stiffness) |
:floppy_disk: [source](https://github.com/mitkof6/musculoskeletal-stiffness/tree/v1.0)

* **SynO: Synergy Optimization** by Mohammad Shourijeh ad Benjamin Fregly (2020). SynO is a collection of MATLAB codes implementing a novel approach for estimating muscle forces/activations by imposing a synergy structure within optimization (termed “synergy optimization”).</br>
:page_facing_up: [paper](https://doi.org/10.1115/1.4044310)
:floppy_disk: [source](https://simtk.org/projects/syno/)

## Subject-Specific Modelling

### Segmentation of Medical Images :art: [WIP]

* **[3DSlicer](https://www.slicer.org/)**
* **[ITK-Snap](http://www.itksnap.org/pmwiki/pmwiki.php)**
* **[Materialise Mimics](https://www.materialise.com/en/medical/mimics-innovation-suite) (commercial)**
* **[MITK](https://docs.mitk.org/2016.11/index.html)**  
* **[MITK-GEM](http://araex.github.io/mitk-gem-site/)** is based on MITK but includes also mesh processing functionalities. Aimed to generation of finite element models. </br>
* **[SASHIMI Segmentation](https://github.com/bartbols/SASHIMI) :sushi:** by Bart Bolsterlee. SASHIMI Segmentation is a MATLAB App for segmentation of multi-slice images. </br> 
* **[Seg3D](https://www.sci.utah.edu/cibc-software/seg3d.html)**    
* **[Simpleware ScanIP](https://www.synopsys.com/simpleware/software/scanip.html)**    

### Manipulation and Processing of Surface Meshes
* [**Autodesk Netfabb**](https://www.autodesk.com/products/netfabb/overview)
* [**Blender**](https://www.blender.org/)
* [**Gmsh**](https://gmsh.info/)
* [**MeshLab**](https://www.meshlab.net/) - **TO ADD PAPER**
* [**MeshMixer**](http://www.meshmixer.com/)
* [**Salome**](https://www.salome-platform.org/user-section/about/mesh)

### Resources for Building Biomechanical Models from Medical Images

* **mri2psm** by Manish Sreenivasa (2016). Open-source toolchain to create patient-specific models from MRI images.  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2016.05.001) (_MRI2PSM, an open-source toolchain to create patient-specific rigid body models from MRI images._ is cited in the paper, but not retrievable). |
:floppy_disk: [source](https://github.com/manishsreenivasa/mri2psm)

* **ModelFactory** by Manish Sreenivasa (2018). A Matlab/Octave toolbox to create human body models.   
:page_facing_up: [preprint](https://arxiv.org/abs/1804.03407) |
:floppy_disk: [source](https://github.com/manishsreenivasa/ModelFactory)

* **Musculotendon parameter optimizer** by Luca Modenese et al. (2016). Optimization based technique that adjusts muscle parameters of musculoskeletal models. It can be used to improve linearly scaled models or to obtain reasonable estimation of optimal fiber lengths and tendon slack lengths in models generated from medical images.  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2015.11.006) |
:dvd: [dataset](link_to_dataset) |
:computer: [website](https://simtk.org/projects/opt_muscle_par) |
:floppy_disk: [source (MATLAB)](https://github.com/modenaxe/MuscleParamOptimizer) |
:floppy_disk: [source (OpenSim plugin)](https://github.com/MuscleOptimizer/MuscleOptimizer) with [documentation](http://muscleoptimizer.github.io/MuscleOptimizer/)

* **NMSBuilder** by Giordano Valente et al. (2017). Freely available software to create subject-specific musculoskeletal models for OpenSim from 3D geometries. NMSBuilder is based on ALBA (Agile Library for Biomedical Applications) an open-source rapid application development framework for computer-aided medicine written in C++.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.cmpb.2017.09.012) |
:computer: [website](http://www.nmsbuilder.org/) |
:movie_camera: [YouTube tutorial](https://www.youtube.com/watch?v=UtAMTFM1vsI)

* **Resources for creating musculoskeletal models from segmentations** by Luca Modenese et al. (2018). This includes materials (step-to-step guide and Matlab scripts) to guide users in creating musculoskeletal models of the lower limb from medical images using a workflow that includes MeshLab, MATLAB and NMSBuilder.</br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2018.03.039) |
:computer: [website](https://simtk.org/projects/subj-spec-model/) |
:page_facing_up: [step-by-step guide](https://figshare.shef.ac.uk/articles/dataset/Data_for_paper_Investigation_of_the_dependence_of_joint_contact_forces_on_musculotendon_parameters_using_a_codified_workflow_for_image-based_modelling_/5863422) |
:floppy_disk: [scripts (MATLAB)](https://figshare.com/articles/Code_for_paper_Investigation_of_the_dependence_of_joint_contact_forces_on_musculotendon_parameters_using_a_codified_workflow_for_image-based_modelling_/6392423)


### Automatic Definition of Bony Landmarks and Reference Systems :skull:

* **Subburaj's curvature/spatial relation matrix method** by Maximilian Fischer et al. (2019). MATLAB implementation of Subburaj's curvature/spatial relation matrix method for the automatic identification of pelvic landmarks.  
:page_facing_up: [Subburaj's paper 2008](https://doi.org/10.3722/cadaps.2008.153-160) |
:page_facing_up: [Subburaj's paper 2009](https://doi.org/10.1016/j.compmedimag.2009.03.001) |
:floppy_disk: [source](https://github.com/RWTHmediTEC/PelvicLandmarkIdentification_Subburaj)

* **Pelvic Landmark Identification** by Maximilian Fischer et al. (2019). This is a fully automatic methods for identification of landmarks on surface models of the pelvis. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3384110.svg)](https://doi.org/10.5281/zenodo.3384110)  
:page_facing_up: [paper](https://www.nature.com/articles/s41598-019-49573-4) |
:floppy_disk: [source](https://github.com/RWTHmediTEC/PelvicLandmarkIdentification)

* **GIBOC-Knee toolbox** by Jean-Baptiste Renault et al. (2018). The toolbox includes three automatic algorithms for reference system identification on femur, tibia and patella. Each algorithm is implemeted with 3 variants, and compared against five other methods from the literature on a dataset of 24 lower-limb CT-scans (not included in the repository).  
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2018.08.028) |
:floppy_disk: [source](https://github.com/renaultJB/GIBOC-Knee-Coordinate-System)

### Uncertainty Quantification in Musculoskeletal Simulations [WIP]

* **Probabilistic Tool for Considering Patient Populations & Model Uncertainty** by Casey A. Myers et al. (2015). This is a probabilistic tool to assess model parameter uncertainty and intersubject variability.  
:page_facing_up: [paper](https://link.springer.com/article/10.1007%2Fs10439-014-1181-7)
:page_facing_up: [Users Guide](https://simtk.org/docman/view.php/886/1884/OpenSim+Probabilistic+Plugin+Users+Guide+%28v1.0%29.pdf)
:computer: [website](https://simtk.org/projects/prob_tool)

* **Probabilistic Musculoskeletal Modeling module (PMM)** by Giordano Valente et al. (2014).  A description is on the supplementary materials of the paper.
:page_facing_up: [paper](https://doi.org/10.1371/journal.pone.0112625)
:computer: [website](https://simtk.org/frs/download_confirm.php/file/4298/PMM_module.rar?group_id=978)


### Meshers of Surface Models
* [TetGen](http://wias-berlin.de/software/index.jsp?id=TetGen&lang=1)
* [NetGen](https://sourceforge.net/projects/netgen-mesher/) [source](https://github.com/NGSolve/netgen)


### Statistical Shape Modelling [WIP]

* **Musculoskeletal Atlas Project (MAP)** by Ju Zhang et al. (2014). Open-source software framework in Python :snake: with plug-in architecture for creating musculoskeletal models. The client-side application (MAP Client) facilitates dicom and motion capture integration, registration tools, and meshing capabilities, and uses statistical shape modelling (based on the Melbourne Femur Collection, which consists of 320 full body CT scans) to provide a best-match to mocap and medical imaging data and generate surface geometry to generate an OpenSim model. **Looks not maintained.**</br>
:page_facing_up: [paper](https://www.researchgate.net/profile/Ju_Zhang15/publication/301951056_The_MAP_Client_User-Friendly_Musculoskeletal_Modelling_Workflows/links/5735044508ae298602df08c8/The-MAP-Client-User-Friendly-Musculoskeletal-Modelling-Workflows.pdf) |
:computer: [website](https://simtk.org/projects/map) |
:computer: [docs](https://map-client.readthedocs.io/en/latest/) |
:floppy_disk: [source](https://github.com/MusculoskeletalAtlasProject/) |
:star: [plugins](https://github.com/mapclient-plugins)

* **Statistical Shape Modelling Research Toolkit (SSMRT)** by Daniel Nolte and the MSk Dynamics group, Imperial College London (2016). The toolkit packages a set of powerful technologies that may be used to predict shape using one of the provided models or to create your own SSM. </br>
:page_facing_up: [paper](https://doi.org/10.1016/j.jbiomech.2016.09.005) |
:computer: [website](https://www.msksoftware.org.uk/software/ssmrt/) 

* **ShapeWorks** by the University of Utah. The ShapeWorks software is an open-source distribution of a new method for constructing compact statistical point-based models of ensembles of similar shapes that does not rely on any specific surface parameterization. </br>
:computer: [website](https://www.sci.utah.edu/software/shapeworks.html)
:floppy_disk: [source](https://github.com/SCIInstitute/ShapeWorks)

* **Shape Model Builder** by Emmanuel Audenaert (2019). Framework to develop shape models in MATLAB. </br>
:page_facing_up: [paper](https://doi.org/10.1080/10255842.2019.1577828) |
:floppy_disk: [source](https://uk.mathworks.com/matlabcentral/fileexchange/49940-shape-model-builder?s_tid=prof_contriblnk)

## Finite Element Analysis

### Finite Element Analysis Software 
* [Abaqus](https://www.3ds.com/products-services/simulia/products/abaqus/) (commercial)
* [Ansys](https://www.ansys.com/en-gb) (commercial)
* [Code_Aster](https://www.code-aster.org/) - see https://www.code-aster.org/UPLOAD/DOC/Presentation/plaquette_aster_en.pdf
* [FEBio](https://febio.org/)
* [Salome_meca](https://www.code-aster.org/spip.php?article303)

### Finite Element Analysis Software Tools

* **GIBBON Toolbox** by [Kevin Moerman](https://kevinmoerman.org/). GIBBON (The Geometry and Image-Based Bioengineering add-On) is an open-source MATLAB toolbox that includes an array of image and geometry visualization and processing tools and is interfaced with free open source software such as TetGen, for robust tetrahedral meshing, and FEBio and Abaqus for finite element analysis. The combination provides a highly flexible image-based modelling environment and enables advanced inverse finite element analysis.  
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.00506)
:computer: [website](https://www.gibboncode.org/) 
:floppy_disk: [source](https://github.com/gibbonCode/GIBBON)

* **LMG: Lumbar Model Generator** by Carolina Lavecchia et al. (2017). LMG is a MATLAB toolbox for semi-automatic generation of lumbar finite element geometries. It generates the geometrical model of the lumbar spine (from the vertebrae L1 to the L5 including the intervertebral disc IVD), the surface models of the bodies involved (STL files) and the solid meshed model, generated with hexahedral elements for the IVD and tetrahedral elements for the vertebrae.</br>
:page_facing_up: [paper](https://royalsocietypublishing.org/doi/pdf/10.1098/rsif.2017.0829)
:floppy_disk: [source](https://github.com/CELavecchia/LMG)

* **ReadySim** by Donald Hume et al. (2020). **TODO: add paper (?) and description**  </br>
:computer: [website](https://simtk.org/projects/readysim)

* **Surrogate Contact Modeling Toolbox** by Ilan Eskinazi and Benjamin Fregly. **TODO: add paper and description**This opensource toolbox provides researchers with the capabilities to construct and use surrogate contact models, including multiple domains for sampling including out-of-contact configurations, a multi-threaded sampler that makes use of FEBio's contact modeling capabilities, flexible specification of surrogate model inputs and outputs, and architecture, parallelized training, testing module and surrogate models portable as DLLs.</br>
:computer: [website](https://simtk.org/projects/scmt/) 

* **Gridap: An extensible Finite Element toolbox in Julia** by Santiago Badia1 and Francesc Verdugo (2020).   
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.02520) |
:page_facing_up: [Users' Guide](https://arxiv.org/abs/1910.01412)
:floppy_disk: [code/source](lhttps://github.com/gridap/Gridap.jl)

### Finite Element Models

* **PIPER Child Human Body Model**: Child finite element model scalable to different ages and posture, used to to study pediatric response to impact. This model is used for crash reconstruction studies.</br>
:page_facing_up: [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0187916) |
:floppy_disk: [source](https://gitlab.inria.fr/piper/child) 

* **Orthotropic Femur Model** by Diogo Geraldes et al. (2015). A complete continuum heterogeneous orthotropic finite element model of the standardised femur, with material properties and directionality resulting from a mechanical loading environment incorporating multiple daily living activities. It is provided as mesh with material properties (similar to Abaqus input file). </br>
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10237-015-0740-7) |
:floppy_disk: [source](https://figshare.com/articles/dataset/Orthotropic_Femur_Model/1419589)

* **The "Standardised Femur" model** by Marco Viceconti.  The standardized femur is the 3D surface model of a femoral bone analogue (mod. #3103) produced by Pacific Research Labs (Vashon Island, Washington, USA) which was for a long while the "de facto" standard in experimental orthopaedic biomechanics. Much experimental data based on this bone analogue are available in the literature; this geometry is proposed as a reference for orthopaedic biomechanics finite element studies. </br>
:page_facing_up: [paper](https://pubmed.ncbi.nlm.nih.gov/8872285/) |
:floppy_disk: [source](https://figshare.shef.ac.uk/articles/The_Standardised_Femur_model/3839766)

* **The "Muscle Standardised Femur" model** by Marco Viceconti. This is a version of the Standardised Femur with muscle insertions modelled as separate regions (surface patches). This makes much easier to create finite element models in which the muscles insertion areas are accurately modelled. </br>
:page_facing_up: [paper1](https://doi.org/10.1016/S0021-9290(02)00175-6) |
:page_facing_up: [paper2](https://doi.org/10.1243%2F09544110360579312) |
:floppy_disk: [source](https://figshare.shef.ac.uk/articles/The_Muscle_Standardised_Femur_model/4578298)

## Statistical Analysis
* [G*Power](https://www.psychologie.hhu.de/arbeitsgruppen/allgemeine-psychologie-und-arbeitspsychologie/gpower.html)
* [spm1d](https://spm1d.org/): package for one-dimensional [Statistical Parametric Mapping](http://www.scholarpedia.org/article/Statistical_parametric_mapping)
* [SPSS Statistics](https://www.ibm.com/uk-en/products/spss-statistics) (commercial)


## Optimal Control and Trajectory Optimization :rocket: [WIP]

* **OpenSim Moco** by Chris Dembia, Nick Bianco and the OpenSim team (2019). OpenSim Moco is a software toolkit to solve optimal control problems with musculoskeletal models defined in OpenSim, including those with kinematic constraints. Using the direct collocation method, Moco can solve a wide range of problems, including motion tracking, motion prediction, and parameter optimization. The design of Moco focuses on ease-of-use, customizability, and extensibility. Just like OpenSim itself, Moco has interfaces in XML/command-line, Matlab, Python, Java, and C++.  
:page_facing_up: [preprint](https://www.biorxiv.org/content/10.1101/839381v1) |
:computer: [website](https://simtk.org/projects/opensim-moco) |
:floppy_disk: [source](https://github.com/opensim-org/opensim-moco) |
:star: [materials from preprint](https://github.com/stanfordnmbl/mocopaper)
:movie_camera: [webinar](https://www.youtube.com/watch?v=IYYZgyE33pU&feature=youtu.be)

* **Rapid 3D muscle-driven predictive simulations** by Antoine Falisse et al. (2019). This framework relies on numerical tools including direct collocation, implicit differential equations, and algorithmic differentiation, and generates predictive simulations of gait in about 35 minutes (single core of a standard laptop computer) with muscle-driven 3D models (29 degrees of freedom and 92 muscles). The code contains a series of example predictive simulations in which we varied objective function, musculoskeletal properties, and gait speed. </br>
:page_facing_up: [paper](https://doi.org/10.1098/rsif.2019.0402) |
:computer: [website](https://simtk.org/projects/3dpredictsim) |
:floppy_disk: [source](https://github.com/antoinefalisse/3dpredictsim) 

* **FROST: Fast Robot Optimization and Simulation Toolkit** by Hereid et al. (2016). FROST for MATLAB provides a general full-body dynamics gait optimization and simulation framework for bipedal walking robots using virtual constraints based feedback controllers. The Wolfram Mathematica backend enables generation of analytic expressions for multi-domain system dynamics and kinematics symbolically, compiled as .MEX files under MATLAB. FROST also features state-of-the-art direct collocation approaches for the full-order dynamics gait optimization problems to guarantee fast and reliable convergence. </br>
:page_facing_up: [paper](https://ieeexplore.ieee.org/document/8202230) |
:computer: [website](http://ayonga.github.io/frost-dev/) |
:floppy_disk: [source](https://github.com/ayonga/frost-dev) 

* **Muscle Redundancy Solver** by Friedl de Groote et al. (2016). An algorithm to estimate muscle tendon properties and/or compute muscle coordination by tracking experimental data with a musculoskeletal model assuming optimal control to solve for the muscle redundancy. </br>
:page_facing_up: [paper](https://link.springer.com/article/10.1007/s10439-016-1591-9) |
:computer: [website](https://simtk.org/projects/optcntrlmuscle) |
:floppy_disk: [source](https://github.com/KULeuvenNeuromechanics/MuscleRedundancySolver) |
:floppy_disk: [dev_repo](https://github.com/antoinefalisse/solvemuscleredundancy_dev)

* **opty** by Jason Moore and Ton van den Bogert (2018). Opty utilizes symbolic descriptions of ordinary differential equations expressed with [SymPy](https://www.sympy.org/en/index.html) to form the constraints needed to solve optimal control and parameter identification problems using the direct collocation method and non-linear programming. </br>
:page_facing_up: [paper](https://joss.theoj.org/papers/10.21105/joss.00300) |
:computer: [documentation](https://opty.readthedocs.io/en/latest/) |
:floppy_disk: [source](https://github.com/csu-hmc/opty) 

* **Data-tracking optimization using collocation** by Yi-Chung Lin and Marcus Pandy (2017). This is a MATLAB package that can be used to perform data-tracking optimization using collocation method. The codes and models are available. The tracking results for one subject during walking and running are also provided. </br>
:page_facing_up: [paper](https://www.ncbi.nlm.nih.gov/pubmed/28583674) |
[:computer: website | :floppy_disk: source ](https://simtk.org/projects/datatracking)

* **Optimal Control of Musculoskeletal Movement Using OpenSim & MATLAB** by Leng-Feng Lee and Brian R. Umberger (2016). This package includes an approach for generating optimal control simulations of human movement using OpenSim and MATLAB based on the direct collocation approach. Models, results and a complete working example are provided. </br>
:page_facing_up: [paper](https://peerj.com/articles/1638.pdf) |
[:computer: website | :floppy_disk: source ](https://simtk.org/projects/directcolloc)


## Societies and Initiatives :office:
* [Americal Society of Biomechanics](https://www.asbweb.org/)
* [European Society of Biomechanics](https://esbiomech.org/)
* [International Society of Biomechanics](https://isbweb.org/)
   * [3-D Analysis of Human Movement](http://www.geocities.ws/3d-ahm/)
   * [Comparative Neuromuscular Biomechanics](https://sites.psu.edu/cnbgroup/)
   * [Footware Biomechanics Group](https://www.footwearbiomechanics.org/)
   * [Hand and Wrist Biomechanics International](https://www.hwbi.org/)
   * [International Shoulder Group](https://isbweb.org/isg)
   * [Motor Control Group](http://www.mcg.isbweb.org/)
   * [Technical Group on Computer Simulation (TGCS)](https://isbweb.org/~tgcs/iscsb-2019/canmore.html)
* [National Biomechanics Day](http://thebiomechanicsinitiative.org/)

## Miscellaneous Online Resources 
* https://www.biomch-l.isbweb.org/
* https://www.biomechanist.net/
* https://biomechsa.wordpress.com/resources
* [ISB Data Resources](http://isbweb.org/data/)
* [Richard Baker's blog](https://wwrichard.net/) (unmaintained).

-----
## Contributing
Have anything in mind that you think is awesome and would fit in this list? Feel free to send a pull request.  
If you are adding elements to the `Dataset` section please use (roughly) this template:

```
* **Template: DatasetName** by Authors (year). Description. [![DOI](yourZenodoDOI)]</br>
:page_facing_up: [paper](doi/link_to_paper) |
:dvd: [dataset](link_to_dataset) |
:computer: [website](link_to_website) |
:floppy_disk: [code/source](link_to_source_code) |
:star: [resources](link_to_resources)
```

-----
## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Luca Modenese](https://uk.linkedin.com/in/luca-modenese-70a54546) has waived all copyright and related or neighboring rights to this work.
