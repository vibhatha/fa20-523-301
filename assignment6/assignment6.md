# Assignment 6
# Health and Medicine – Artificial Intelligence Influence on Ischemic Stroke Imaging

* Gavin Hemmerlein, fa20-523-301 
* [Edit](https://github.com/cybertraining-dsc/fa20-523-301/blob/master/assignment6/assignment6.md)

**Keywords:** convolutional neural network, random forest learning, Computer Tomography Scan, CT Scan, stroke, artificial intelligence, deep learning, machine learning, large vessel occlusions

## 1. Introduction

The Computer Tomography Scan (CT Scan) is a medical procedure that involves multiple x-rays analyzed using computer aided techniques. The CT Scan’s creation was credited to Allan M. Cormack and Godfrey N. Hounsfield for which both individuals were awarded the 1979 Nobel Prize in Physiology or Medicine [^1]. The OECD estimates that there are a total of 42.64 million scanners located in the United States; the fourth most of any country [^2]. This prevalence is extremely important when discussing a diagnosis for stroke victims. In the 1980s, the identification techniques were generally done through a process called computer-aided diagnosis (CAD). “CAD usually relies on a combination of interpretation of medical images through computational algorithms and the physicians’ evaluation of the medical images [^3]”.

The goal of researchers and medical practitioners is to improve upon detection rates to ensure that more lives are saved by early detection. According to Johns Hopkins Medical Department the faster medical precautions can be given to a victim, the better the prognosis is for the individual [^4]. The brain requires a constant supply of blood and oxygen. When it is starved of these nutrients, the brain tissue begins to die. 

## 2. Assisting Researchers with Artificial Intelligence 

According to an article in Radiology Business, automated detection of stroke anomalies is improving. As stated in a review in the article, “the team found convolutional neural networks beat random forest learning (RFL) on sensitivity, 85% to 68% [^5].” This improvement is an excellent improvement by switching the algorithm that is used to train the model. A convolutional neural network (CNN) is a deep learning technique while a random forest is a modified decision tree. By modifying approaches from a decision tree to a deep learning technique, there is a very high likelihood that more lives could be saved. Strokes account for nearly 140,000 deaths a year and are one of the leading causes of permanent disability in the United States [^6].

A RFL algorithm is a form of decision tree supervised learning. Decision trees are unique because they can also be used to solve regression and classification problems; which is unique to supervised learning methods. The RFL uses many decision trees that build upon one another. Where the CNN algorithm differs is that it is a form of deep learning that performs unsupervised learning. Each layer in the CNN understands its inputs and outputs while passing the output on to the next layer. A CNN can pass this information forward through a number of layers, but there is also a diminishing return given the amount of processing needed for each layer.

After reviewing the literature from the Radiology Business article, the most common avenue for early detection appears to be the RFL as stated above. A meta analysis reviewing PubMed articles from January 2014 to February 2019 found that the RFL was the highest performer for predictive measures [^7]. For large vessel occlusions (LVO), the best approach was to use a CNN. CNN’s use little pre-processing and rely moreso on the filters with the data. This results in a more dynamic approach to the data as opposed to the harder developed structure of a decision tree.  

## 3. Future Work

Upon examining the cited sources, there are some future areas to look research. To improve on current understanding, a standardization of metrics for to evaluate the fidelity of the models [^5], continued development of automative image analysis software [^3], and leveraging emerging techniques to develop even more effective algorithms to detect large vessel occlusion [^8]. As of 2019, the advantage of CNN’s over conventional detection methods was only 7.6% [^9]. The percentage may seem marginal, but when expanded out to the 140,000 strokes per year the amount of strokes identified could be as much as 10,000 individuals.

These areas are only a few of the many improvements that could be made in the world of stroke detection. It is not a far stretch to imagine detecting vessels that are becoming clogged or brittle. If detection of these medical issues could become prevalent, even more lives could be saved by predicting strokes before they even occur.

## 4. References

[^1]: Nobel Prizes & Laureates, "The Nobel Prize in Physiology or Medicine 1979," *The Nobel Prize,* [Online]. Available:
 <https://www.nobelprize.org/prizes/medicine/1979/summary/> [Accessed Oct. 16, 2020].

[^2]: OECD, "Computed tomography (CT) scanners," *OECD Data,* [Online]. Available:
 <https://data.oecd.org/healtheqt/computed-tomography-ct-scanners.htm> [Accessed Oct. 16, 2020].

[^3]: Y. Mokli, J. Pfaff, D. Pinto dos Santos, C. Herweh, and S. Nagel "Computer-aided imaging analysis in acute ischemic stroke – background and clinical applications", *Neurological Research and Practice*, p. 1-13. 2020 [Online serial]. Available:  <https://neurolrespract.biomedcentral.com/track/pdf/10.1186/s42466-019-0028-y> [Accessed Oct. 13, 2020].

[^4]: A. Pruski, “Stroke Recovery Timeline,” *John Hopkins Medical,* [Online]. Available: <https://www.hopkinsmedicine.org/health/conditions-and-diseases/stroke/stroke-recovery-timeline> [Accessed Oct. 16, 2020].

[^5]: D. Pearson, "AI helps bust stroke, identify occlusions," *Radiology Business,* [Online]. Available:
 <https://www.radiologybusiness.com/topics/artificial-intelligence/ai-helps-bust-stroke-identify-occlusions> [Accessed Oct. 13, 2020].

[^6]: The Internet Stroke Center, "About Strokes," *Stroke Statistics,* [Online]. Available:
 <http://www.strokecenter.org/patients/about-stroke/stroke-statistics/#:~:text=More%20than%20140%2C000%20people%20die,and%20185%2C000%20are%20recurrent%20attacks> [Accessed Oct. 16, 2020].

[^7]: N. Murray, "Artificial intelligence to diagnose ischemic stroke and identify large vessel occlusions: a systematic review," *Journal of NeuroInterventional Surgery*, vol. 12, no. 2, p. 156-164. 2020 [Online serial]. Available: <https://jnis.bmj.com/content/12/2/156> [Accessed Oct. 13, 2020].

[^8]: M. Stib, J. Vasquez, M. Dong, Y. Kim, S. Subzwari, H. Triedman, A. Wang, H. Wang, A. Yao, M. Jayaraman, J. Boxerman, C. Eickhoff, U. Cetintemel, G. Baird, and R. McTaggart, "Detecting Large Vessel Occlusion at Multiphase CT Angiography by Using a Deep Convolutional Neural Network", *Original Research Neuroradiology*, Sep 29, 2020. [Online serial]. Available: <https://pubs.rsna.org/doi/full/10.1148/radiol.2020200334> [Accessed Oct. 13, 2020].

[^9]: J. Tuan, "How AI is able to Predict and Detect a Stroke", *Referral MD*. [Online]. Available: <https://getreferralmd.com/2019/10/how-ai-is-able-to-predict-and-detect-a-stroke/> [Accessed Oct. 13, 2020].
