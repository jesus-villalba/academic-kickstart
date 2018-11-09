+++
title = "Preventing Replay Attacks on Speaker Verification Systems"
date = 2011-09-01
authors = ["Jesús Villalba", "Eduardo Lleida"]
publication_types = ["1"]
abstract = "In this paper, we describe a system for detecting spoofing attacks on speaker verification systems. We understand as spoofing the fact of impersonating a legitimate user. We focus on detecting two types of low technology spoofs. On the one side, we try to expose if the test segment is a far-field microphone recording of the victim that has been replayed on a telephone handset using a loudspeaker. On the other side, we want to determine if the recording has been created by cutting and pasting short recordings to forge the sentence requested by a text dependent system. This kind of attacks is of critical importance for security applications like access to bank accounts. To detect the first type of spoof we extract several acoustic features from the speech signal. Spoofs and non-spoof segments are classified using a support vector machine (SVM). The cut and paste is detected comparing the pitch and MFCC contours of the enrollment and test segments using dynamic time warping (DTW). We performed experiments using two databases created for this purpose. They include signals from land line and GSM telephone channels of 20 different speakers. We present results of the performance separately for each spoofing detection system and the fusion of both. We have achieved error rates under 10$backslash$% for all the conditions evaluated. We show the degradation on the speaker verification performance in the presence of this kind of attack and how to use the spoofing detection to mitigate that degradation."
selected = true
publication = "*Proceedings of the IEEE International Carnahan Conference on Security Technology, ICCST 2011*"
tags = ["and paste", "cut", "far-field", "forgery", "replay attack", "speaker verification", "spoofing"]
url_pdf = "http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6095943&tag=1"
doi = "10.1109/CCST.2011.6095943"
+++

