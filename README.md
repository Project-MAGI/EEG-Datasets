# EEG Datasets for Project MAGI
> The overall requirement is that data can't be less than 10-20 montages. This won't be a complete list for all EEG datasets. Instead, we only want it to be an internal reference.

* **Motor-Imagery**
  1. [Left/Right Hand MI](http://gigadb.org/dataset/100295):  Includes 52 subjects (38 validated subjects with discriminative features), results of physiological and psychological questionnaires, EMG Datasets, location of 3D EEG electrodes, and EEGs for non-task related states
  2. [Motor Movement/Imagery Dataset](https://www.physionet.org/content/eegmmidb/1.0.0/): Includes 109 volunteers, 64 electrodes, 2 baseline tasks (eye-open and eye-closed), motor movement, and motor imagery (both fists or both feet)
  3. [Grasp and Lift EEG Challenge](https://www.kaggle.com/c/grasp-and-lift-eeg-detection/data): 12 subjects, 32channels@500Hz, for 6 grasp and lift  events, namely a). HandStart b). FirstDigitTouch c). Both StartLoadPhase d). LiftOff e). Replace  f). BothReleased
  4. [The largest SCP data of Motor-Imagery](https://doi.org/10.6084/m9.figshare.c.3917698): The dataset contains 60 hours of EEG BCI recordings across 75 recording sessions of 13 participants, 60,000 mental imageries, and 4 BCI interaction paradigms, with multiple recording sessions and paradigms of the same individuals. BCI interactions involving up to 6 mental imagery states are considered. [[Article]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6190745/pdf/sdata2018211.pdf)
  5. [BCI Competition IV-1](http://www.bbci.de/competition/iv/#dataset1): 64 EEG channels at 1000Hz sampling rate for 2 classes of left hand, right hand, foot (+ idle state) for 7 subjects. Evaluation data is continuous EEG which contains also periods of idle state.
  6. [BCI Competition IV-2a](http://www.bbci.de/competition/iv/#dataset2a): 22-electrode EEG motor-imagery dataset,  with 9 subjects and 2 sessions, each with 288 four-second trials of imagined movements per subject. Includes movements of the left hand, the right hand, the feet and the tongue. [[Dataset Description]](http://www.bbci.de/competition/iv/desc_2a.pdf)
  7. [High-Gamma Dataset](https://github.com/robintibor/high-gamma-dataset): 128-electrode dataset obtained from 14 healthy subjects with roughly 1000 four-second trials of executed movements divided into 13 runs per subject.  The four classes of movements were movements of either the left hand, the right hand, both feet, and rest.
  8. [Imagination of Right-hand Thumb Movement](https://archive.ics.uci.edu/ml/datasets/Planning+Relax): In every trial, subjects were asked to rest and rest data was recorded for 5 mins. Further, 5 second epoch data was also recorded when subjects were asked to imagine right hand thumb movement. 5 of such imagined motor movement, and rest state was recorded for each trial. Single subject, 8 electrodes at 256Hz.
  9. [Mental-Imagery Dataset](https://figshare.com/collections/A_large_electroencephalographic_motor_imagery_dataset_for_electroencephalographic_brain_computer_interfaces/3917698): 13 participants with over 60,000 examples of motor imageries in 4 interaction paradigms recorded with 38 38-channel medical-grade EEG system. It contains data for upto 6 mental imageries primarily for the motor movements. [[Article]](https://www.nature.com/articles/sdata2018211#ref-CR57)    
  
* **Emotion-Recognition**
  1. [DEAP](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/): Includes 32 subjects, each watching 1-min long excerpts of music-videos, rated by users in terms of arousal/valence/like-dislike/dominance/familiarity, and frontal face recording of 22/32 subjects.
  2. [Enterface'06](http://www.enterface.net/results/): Enterface'06 Project 07: EEG(64 Channels) + fNIRS + face video, Includes 16 subjects, where emotions were elicited through selected subset of IAPS dataset.
  3. [Imagined Emotion](http://headit.ucsd.edu/studies/3316f70e-35ff-11e3-a2a9-0050563f2612): 31 subjects, subjects listen to voice recordings that suggest an emotional feeling and ask subjects to imagine an emotional scenario or to recall an experience in which they have felt that emotion before.
  4. [SEED](http://bcmi.sjtu.edu.cn/~seed/seed.html): 15 subjects were shown video clips eliciting positive/negative/neutral emotion and EEG was recorded over 62 channels.
  5. [SEED-IV](http://bcmi.sjtu.edu.cn/~seed/seed-iv.html): 15 subjects were shown video clips eliciting happy/sad/neutral/fear emotions, and EEG was recorded over 62 channels (with eye-tracking) for 3 sessions per subject (24 trials per session).
  6. [SEED-VIG](http://bcmi.sjtu.edu.cn/~seed/seed-vig.html): Vigilance labels with EEG data in a simulated driving task. 18 electrodes and eye-tracking included.
  7. [HCI-Tagging](https://mahnob-db.eu/hci-tagging/): Subjects were shown video clips (fragments of movies) and they were asked to annotate the emotional state on the scale of valence and arousal. During the whole experiment, audio, video, gaze data, and physiological data were recorded simultaneously with accurate synchronisation between sensors.
  8. [Regulation of Arousal](https://ieee-dataport.org/open-access/regulation-arousal-online-neurofeedback-improves-human-performance-demanding-sensory): 18 subjects going through an online flight simulator study with three different audio-feedback silence, sham, and BCI. [[Article]](https://www.pnas.org/content/116/13/6482)
  9. [Leipzig Mind-Brain-Body Dataset - LEMON](https://fcon_1000.projects.nitrc.org/indi/retro/MPI_LEMON/downloads/download_EEG.html)
  
  
* **Error-Related Potentials (ErrP)**
  1. [BCI-NER Challenge](https://www.kaggle.com/c/inria-bci-challenge): 26 subjects, 56 EEG Channels for a P300 Speller task, and labeled dataset for the response elicited when P300 decodes a correct or incorrect letter.
  2. [Monitoring ErrP in a target selection task](http://bnci-horizon-2020.eu/database/data-sets): 6 subjects with 64 EEG electrodes, watching a cursor move towards a target square, and elicited responses are labeled based on whether the cursor moves in right or wrong direction. [[Dataset Description]](https://lampx.tugraz.at/~bci/database/013-2015/description.pdf)
  3. [ErrPs during continuous feedback](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/contErrP_description.pdf): 10 subjects with 28 EEG electrodes, playing a video game to study execution and outcome error. [[Dataset Part-1]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part1.rar) [[Dataset Part-2]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part2.rar)
  4. [HCI-Tagging](https://mahnob-db.eu/hci-tagging/): Subjects were shown images or movie fragments with a tag at the bottom of the screen. In some cases, the tag correctly described something about the situation. However, in other cases, the tag did not apply to the media item. After each item, a participant was asked to press a green button if they agreed with the tag applying to the media item, or press a red button if not. During the whole experiment, audio, video, gaze data, and physiological data were recorded simultaneously with accurate synchronisation between sensors.
  5. [Error Related Potentials from Gaze-Based Typesetting](https://www.mamem.eu/results/datasets/)
  6. [BrainInvader](https://arxiv.org/pdf/1905.05182): P300 Brain-Computer Interface inspired by the famous vintage video game Space Invaders (https://zenodo.org/records/2649069) and https://sites.google.com/site/marcocongedo/science/eeg-data
  
* **Visually Evoked Potentials (VEPs)**
  1. [c-VEP BCI](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_dataset.rar): 9 subjects, 32 EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Dataset description]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_description.pdf) [[Published article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0051077)
   2. [c-VEP BCI with dry electrodes](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/dry_cVEP_dataset.rar): 9 subjects, 15 dry-EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0172400)
   3. [Synchronized Brainwave Dataset](https://www.kaggle.com/berkeley-biosense/synchronized-brainwave-dataset): 15 people were presented with 2 different video stimulus including blinks, relaxation, mental mathematics, counting color boxes, and watching superbowl ads. [[Stimulus 1]](https://www.youtube.com/watch?v=zkGoPdpRvaU&feature=youtu.be) [[Stimulus 2]](https://www.youtube.com/watch?v=sxqlOoBBjvc&feature=youtu.be)
   4. [MAMEM SSVEP](https://www.physionet.org/content/mssvepdb/1.0.0/)
   5. [Visually Evoked Potential EEG](https://www.nitrc.org/projects/vep_eeg_raw) An 18-subject EEG dataset from an experiment in which subjects performed a standard visual oddball task.

  
* **Event Related Potentials [ERPs]**
  1. [Pattern Visual Evoked Potentials](https://www2.le.ac.uk/departments/engineering/research/bioengineering/neuroengineering-lab/software): Dataset#5, 2 subjects for checkboard light pattern (oddball paradigm) recorded at O1 position. 
  2. [Face vs. House Discrimination](https://purl.stanford.edu/xd109qh3109): 7 Epileptic subjects were presented with 50  grayscale stimulations each for Face and House pictures. For each subject, a total of 3 experimental runs were conducted, resulting in 300 stimulations. 
  6. [Target Versus Non-Target](https://zenodo.org/record/3267302): 38 subjects playing a multiplayer and collaborative version of Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adaptive Riemannian Geometry (no-calibration). 32 electrodes per subject, wet, 2 subjects during each session. [publication](https://hal.archives-ouvertes.fr/hal-02173958), [code](https://github.com/plcrodrigues/py.BI.EEG.2014b-GIPSA). Dataset id: bi2014b.
  7. [Target Versus Non-Target](https://zenodo.org/record/3266930): 50 subjects playing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adaptive Riemannian Geometry (no-calibration). 32-electrodes, wet. 3 sessions per subject with modulation of flash duration. [publication](https://hal.archives-ouvertes.fr/hal-02172347), [code](https://github.com/plcrodrigues/py.BI.EEG.2015a-GIPSA). 
  8. [Target Versus Non-Target](https://zenodo.org/record/3268762): 44 subjects playing a multiplayer (cooperation and competition) version of Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adaptive Riemannian Geometry (no-calibration). 32 electrodes per subject, wet, 2 subjects for each session. [publication](https://hal.archives-ouvertes.fr/hal-02173913), [code](https://github.com/plcrodrigues/py.BI.EEG.2015b-GIPSA). Dataset id: bi2015b.
  9. [Impedance Data](https://erpinfo.org/impedance): 12 subjects for P300 task (Oddball paradigm) with 20% of rare stimuli. In total, there were 128 target stimuli and 512 standard stimuli. The dataset was collected in a way such that one recording contains different impedances in the electrodes. [[Article]](https://static1.squarespace.com/static/5abefa62d274cb16de90e935/t/5ac6962a8a922d0b8b8be6a1/1522964012664/Kappenman+2010+Psychophys+Impedance.pdf) [[Data]](https://erpinfo.org/impedance)
  10. [Sustained-Attention Driving Task (SADT)](https://figshare.com/articles/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task/6427334/5): 27 subjects for sustained-attention driving in a VR setting for monitoring event-related potentials. Each subject participated in two 90-minute sessions (with and without kinesthetic feedback) and was recorded with 32 channels and 500Hz. [[Article]](https://www.nature.com/articles/s41597-019-0027-4#Sec12) [[Pre-processed dataset]](https://figshare.com/articles/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task_preprocessed_dataset_/7666055/3)
  11. [Dryad-Speech](https://datadryad.org/stash/dataset/doi:10.5061/dryad.070jc): 5 different experiments for studying natural speech comprehension through a variety of tasks including audio, visual stimulus and imagined speech. (i) Audio-book version of a popular mid-20th century American work of fiction - 19 subjects, (ii) presentation of the same trials in the same order, but with each of the 28 speech segments played in reverse, (iii) N400 experiment: subjects read 300 sentences presented  with the rest of the sentence and half which ended with an incongruent word - , (iv) cocktail party experiment: 33 subjects undertook 30 trials, each of 60 s in length, where they were presented with 2 classic works of fiction: one to the left ear, and the other to the right ear. Subjects were divided into 2 groups of 17 and 16 (+1 excluded subject) with each group instructed to attend to the story in either the left or right ear throughout the entire 30 trials, (v) multisensory experiment:  stimuli were drawn from a set of videos that consisted of a male speaking American English in a conversational-like manner. [[Main Article]](https://www.sciencedirect.com/science/article/pii/S0960982218301465) [[Supplemntary Article]](https://www.ncbi.nlm.nih.gov/pubmed/26412129)
  12. [ERP Core](https://github.com/andrewxstewart/ERP_CORE) 6-7 ERP paradigms including N170, N400, LRP/ERN, etc., from 40 participants, includes analysis scripts, experiments, results, and data. [[Article]](https://psyarxiv.com/4azqm/) [[Website]](https://erpinfo.org/erp-core)
  13. [Robust Detection of Event-Related Potentials in a User-Voluntary Short-Term Imagery Task](https://figshare.com/articles/dataset/EEG_dataset/8091242)
  14. [The Nencki-Symfonia EEG/ERP dataset: Multiple cognitive tasks and resting-state data collected in a sample of healthy adults](http://gigadb.org/dataset/100990)
  15. [ERP CORE: An Open Resource for Human Event-Related Potential Research](https://osf.io/thsqg/)

* **Resting State**
  1. [Resting State EEG Data](https://dataverse.tdl.org/dataverse/txstatecogelectro): 22 subjects, 72 EEG Channels for a resting task of 8 mins with 4 mins of eyes closed and 4 mins of eyes open. [[Article]](https://www.frontiersin.org/articles/10.3389/fnins.2017.00425)
  2. [SPIS Resting State Dataset](https://github.com/mastaneht/SPIS-Resting-State-Dataset): 10 subjects, 64 channels, 2.5 minutes recording in each state (eyes-closed and eyes-open) prior to a 105-minute session of Sustained Attention to Response Task with fixed-sequence and varying ISIs. [[Article]](https://www.ncbi.nlm.nih.gov/pubmed/32167917)
  
* **Auditory Stimulus**
  1. [OpenMIIR](https://github.com/sstober/openmiir): 10 subjects, 64 EEG Channels for a music imagery task of 12 different pieces w/ different meter, length and tempo. [[Article]](https://pdfs.semanticscholar.org/cde4/b1ec89f2c05a41f1143792a890a00e89541a.pdf)
  2. [NMED-T](https://exhibits.stanford.edu/data/catalog/jn859kj8079)
  3. [NMED-H](https://exhibits.stanford.edu/data/catalog/sd922db3535)
  4. [NMED-M](https://exhibits.stanford.edu/data/catalog/kt396gb0630)
  5. [NMED-E](https://exhibits.stanford.edu/data/catalog/pp371jh5722)
  6. [NMED-RP](https://exhibits.stanford.edu/data/catalog/rz763kn3821)
  7. [EEG-Recorded Responses to Short Chord Progressions](https://purl.stanford.edu/js383fs8244)
  8. [Characterization of auditory steady state brain responses in time, frequency and space](https://data.ru.nl/collections/di/dccn/DSC_3015000.00_810)
  9. [Auditory EEG](https://www.physionet.org/content/auditory-eeg/1.0.0/)

* **Visual Stimulus**
  1. [MNIST Brain Digits](http://mindbigdata.com/opendb/index.html): EEG data when a digit(0-9) is shown to the subject, recorded 2s for a single subject using Minwave, EPOC, Muse, Insight. Includes over 1.2M samples. 
  2. [Imagenet Brain](http://www.mindbigdata.com/opendb/imagenet.html): A random image is shown (out of 14k images from the Imagenet ILSVRC2013 train dataset) and EEG signals are recorded for 3s for one subject. Includes over 70k samples.
  3. [EEG-ImageNet](https://github.com/Promise-Z5Q2SQ/EEG-ImageNet-Dataset)
  4. [ThoughtViz](https://github.com/ptirupat/ThoughtViz): consists of 10 different object classes, which is a subset of the ImageNet
  5. [A Representational Similarity Analysis of the Dynamics of Object Processing Using Single-Trial EEG Classification](https://purl.stanford.edu/bq914sc3730)
  6. [Visual Decoding and Reconstruction via EEG Embeddings with Guided Diffusion](https://github.com/ncclab-sustech/EEG_Image_decode)
  7. [SEED-DV](https://bcmi.sjtu.edu.cn/home/eeg2video/)
  8. [THINGS-EEG](https://figshare.com/articles/dataset/THINGS-EEG/14721282)
  9. [THINGS-EEG2](https://osf.io/3jk45/)
  10. [EEG human categorization data](https://www.nitrc.org/projects/eegdataanimal) Subjects are performing a go-nogo categorization task and a go-no recognition task on natural photographs presented very briefly
  
* **Eye-blinks/movements**
  1. [Involuntary Eye Movements during Face Perception](http://www2.hu-berlin.de/eyetracking-eeg/testdata.html): Dataset 1, 26 electrodes, 500Hz sampling rate, and 120 trials. Eye movements and pupil diameter record, EEG and EOG data is present when subject is presented a happy/sad/angry face on the screen. [[Article]](http://www.jneurosci.org/content/suppl/2009/09/30/29.39.12321.DC1/Supplemental_Material.pdf) [P.S: Dataset available on request only]
  2. [Voluntary-Involuntary Eye-Blinks](https://drive.google.com/file/d/0By5iwWd39NblS2tRWmVTdmRzZUU/view?usp=sharing): Voluntary eye-blinks (subjects were asked to blink voluntarily within 1s of the audio stimulus) and involuntary eye-blinks (natural) were recorded for 20 subjects on 14 electrodes using g.tec. For each subject, 3 sessions with 20 trials each are present in .mat format. [[Article]](https://www.sciencedirect.com/science/article/pii/S0925231216001569)
  3. [EEG-IO](http://gnan.ece.gatech.edu/eeg-eyeblinks/): Voluntary single eye-blinks (external stimulation was provided) and EEG was recorded for frontal electrodes (Fp1, Fp2) for 20 subjects using OpenBCI Device and BIOPAC Cap100C. One session was conducted, including around 25 blinks per subject. Manual annotation was done using video feed. [[Article]](https://proceedings.allerton.csl.illinois.edu/media/files/0174.pdf)
  4. [EEG-VV, EEG-VR](http://gnan.ece.gatech.edu/eeg-eyeblinks/): Involuntary eye-blinks (natural blinks) and EEG was recorded for frontal electrodes (Fp1, Fp2) for 12 subjects using OpenBCI Device and BIOPAC Cap100C. Subjects performed two activities - watching a video (EEG-VV) and reading an article (EEG-VR). Manual annotation was done using video feed. [[Article]](https://proceedings.allerton.csl.illinois.edu/media/files/0174.pdf)
  5. [Kara-One](http://www.cs.toronto.edu/~complingweb/data/karaOne/karaOne.html): Imagined and vocalized phonemic and single-word prompts to access the language and speech production. 14 subjects recorded using a 64-channel Neuroscan Quick-Cap, along with face tracking and audio. [[Article]](http://www.cs.toronto.edu/~complingweb/data/karaOne/ZhaoRudzicz15.pdf)
  6. [EEGEyeNet](https://openreview.net/forum?id=Nc2uduhU9qa): EEG and Eye Tracking recordings from 356 different subjects collected from three different experimental paradigms (left-right, angle-amplitude and absolute position) and with 128-channels. [[Article]](https://openreview.net/forum?id=Nc2uduhU9qa) [[Data]](https://osf.io/ktv7m/)
  7. [mEBAL](https://github.com/BiDAlab/mEBAL): A multimodal database for eye blink detection and attention level estimation. NIR + RGB Cameras + EEG signals from 38 students, comprising 3000 blink samples. [[Article]](https://arxiv.org/pdf/2006.05327.pdf) [[Data]](https://github.com/BiDAlab/mEBAL)
  8. [CWL EEG fMRI Data Set](https://www.nitrc.org/projects/cwleegfmri_data) 8 subject doing a simple eyes open/eyes closed

* **Artifact Removing / Denoising (Important)**
  1. [EEGdenoisenet](https://github.com/ncclabsustech/EEGdenoiseNet)
  2. [Semi-Simulated EEG/EOG](https://github.com/WilliamRo/EEG-Denoise)
  3. [EEGDiR Denoising Dataset](https://www.sciencedirect.com/science/article/abs/pii/S001048252400711X)
  4. [Motion Artifact Contaminated fNIRS and EEG Data](https://www.physionet.org/content/motion-artifact/1.0.0/)

* **Miscellaneous**
  1. [Working Memory](https://github.com/pbashivan/EEGLearn/tree/master/Sample%20data): Participants briefly observe an array containing multiple English characters SET (500ms) and maintain the information for three seconds. A TEST character is then presented and participants respond by press of a button if TEST charter matches one of the characters in the SET. 15 students, 64 electrodes, and a 500Hz sampling rate. Only a small subset of data is available publicly. [[Original Paper]](https://www.memphis.edu/acnl/publications/pdfs/ejn2014b.pdf) [[Further Analysis in ICLR]](https://arxiv.org/pdf/1511.06448.pdf)
  2. [Confusion during MOOC](https://www.kaggle.com/wanghaohan/confused-eeg): 10 students watching MOOC videos in two categories - non-confusing (e.g., basic maths) and confusing (e.g., quantum theory). 2-minute duration, 10 videos in each category. Recorded from a single-channel wireless MindSet over the frontal channel. [[Article]](http://www.cs.cmu.edu/~kkchang/paper/WangEtAl.2013.AIED.EEG-MOOC.pdf) 
  3. [The Nencki-Symfonia EEG/ERP dataset](https://www.kaggle.com/datasets/patrycjadzianok/nencki-symfonia-eeg-erp-dataset): high-density electroencephalography (EEG) dataset obtained at the Nencki Institute of Experimental Biology from a sample of 42 healthy young adults with three cognitive tasks: (1) an extended Multi-Source Interference Task (MSIT+) with control, Simon, Flanker, and multi-source interference trials; (2) a 3-stimuli oddball task with frequent standard, rare target, and rare distractor stimuli; (3) a control, simple reaction task (SRT); and additionally (4) a resting-state protocol (REST). [[Data]](http://doi.org/10.5524/100990) - [[Paper]](https://doi.org/10.1093/gigascience/giac015)
  4. [ZuCo](https://www.nature.com/articles/sdata2018291): EEG and eye-tracking recording for 12 healthy adult native English speakers, each reading natural English text for 4–6 hours. 21,629 words in 1107 sentences and 154,173 fixations.  [[Paper]](https://www.nature.com/articles/sdata2018291) [[Data]](https://osf.io/2urht/)
  5. [MAMEM Phase I Dataset – A dataset for multimodal human-computer interaction using biosignals and eye tracking information](https://figshare.com/articles/MAMEM_Phase_I_Dataset_-_A_dataset_for_multimodal_human-computer_interaction_using_biosignals_and_eye_tracking_information/5231053)
  6. [HBN - Healthy Brain Networks](https://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/MRI_EEG.html)
  7. [TDBrain Dataset](https://brainclinics.com/resources/) The TDBrain dataset is a dataset of EEG data for 1200 subjects.
  8. [Multimodal Resource for Studying Information Processing in the Developing Brain (MIPDB)](https://fcon_1000.projects.nitrc.org/indi/cmi_eeg/index.html)
  9. [ Cuban Human Brain Mapping ](https://www.synapse.org/Synapse:syn22324937)
  10. [ Latin American Brain Health Institute ](https://www.synapse.org/Synapse:syn51549340/wiki/624187)
  11. [EEG During Mental Arithmetic Tasks](https://www.physionet.org/content/eegmat/1.0.0/)

* **Clinical EEG**
  1. [TUH EEG Resources](https://www.isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml): Massive amount of data for (i) Abnormal EEG and (ii) EEG Seizures
  2. [Predict-UNM](http://predict.cs.unm.edu/): A large repository of clinical EEG datasets
  3. [Alchoholic Dataset](https://kdd.ics.uci.edu/databases/eeg/eeg.html)  It contains measurements from 64 electrodes placed on the scalp sampled at 256 Hz (3.9-msec epoch) for 1 second.
  4. [Freiburg epilepsy dayaset](http://epilepsy.uni-freiburg.de/freiburg-seizure-prediction-project/eeg-database)
  5. [ADHD Dataset](https://nda.nih.gov/study.html?id=1938)
  6. [pre- and postsurgical EEG recorded from epilepsy patients and HFO markings](https://gin.g-node.org/USZ_NCH/Scalp_EEG_HFO)
  7. [A dataset of neonatal EEG recordings with seizures annotations](https://zenodo.org/records/2547147)
  8. [Resting State EEG Biomarkers of Cognitive Decline (PLOS ONE - INSPECDS)](https://data.mendeley.com/datasets/wttpypkctg/2)
  9. [CHB-MIT Scalp EEG Database](https://www.physionet.org/content/chbmit/1.0.0/) a collection of EEG recordings of 22 pediatric subjects with intractable seizures
  10. [I-CARE: International Cardiac Arrest REsearch consortium Database](https://www.physionet.org/content/i-care/2.1/)

* **Clinical: Sleeping**
  1. [Deep Sleep Slow Osciallation](https://challengedata.ens.fr/challenges/10): 10 seconds of recording starting 10 seconds before the end of a slow oscillation. Data is recorded to predict whether or not a slow oscillation will be followed by another one in the sham condition, i.e., without any stimulation.
  2. [DREAM: A Dream EEG and Mentation Database](https://bridges.monash.edu/projects/The_Dream_EEG_and_Mentation_DREAM_database/158987)
  3. [SleepEDF](https://www.physionet.org/content/sleep-edf/1.0.0/)
  4. [SleepEDF-X](https://www.physionet.org/content/sleep-edfx/1.0.0/)

### Others [Unfiltered]
  1. https://www.physionet.org/about/database/
  2. [PREDICT - Patient Repository for EEG Data + Computational Tools](http://predict.cs.unm.edu/downloads.php)
  3. http://bnci-horizon-2020.eu/database/data-sets
  4. BIDS dataset: https://github.com/bids-standard/bids-examples https://osf.io/cj2dr/ https://zenodo.org/record/2536267 https://osf.io/dvmrb/
  5. Another platform for Neuro datasets: https://openneuro.org/ and https://NEMAR.org (Is there a difference if I download data from NEMAR or OpenNeuro? No, there is no difference between the data being downloaded. NEMAR download only offers ZIP file downloads, while OpenNeuro offers a variety of advanced methods. We made ZIP download available because of the problem people sometimes encounter on OpenNeuro. Also, OpenNeuro uses the Amazon cloud, and download speeds are usually about ten times slower than transfers from the San Diego Supercomputer Center.)
  6. https://thinquanaut.wordpress.com/open-data-sources/
  7. https://osf.io/bndjg/ Article: https://www.ncbi.nlm.nih.gov/pubmed/25450163
  8. https://github.com/openlists/ElectrophysiologyData
