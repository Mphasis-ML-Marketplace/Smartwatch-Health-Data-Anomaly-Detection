# Smartwatch-Health-Data-Anomaly-Detection

This solution uses an unsupervised anomaly detection approach to identify suspect health metrics in a person using their smartwatch data.

## Product overview

This solution utilizes unsupervised outlier detection methods to detect anomalous health events from multiple sensors providing their heart rate and steps data sequenced over a period of time. Such an approach does not require labelling, as the model learns to detect anomalous values from the provided distribution itself. This provides a convenient method for preemptive analysis making use of limited, relatively easily available data. The solution is meant to provide a quick risk assessment, and should not be used as a diagnostic test. If you believe you are ill, please get medical assistance.

## Product Highlight 

* In the case of unlabelled data in the healthcare domain, it is essential to be able to accurately diagnose, analyse and determine the problem at hand, despite the lack of labels for specific training. Multiple sources of data, such as heart rate and steps such as considered here, help with increasing the feature space for better model learning. An algorithm was devised to use the different types of together, and an outlier detection model is trained on the derived data values. This model allows us to robustly detect the presence of any outliers in the multimodal data.  

* This solution provides a way of preemptive evaluation given any patient's data. Detecting anomalous values with a high recall rate (minimum false negatives) which indicate the potential of the onset of a health event is quite useful as a precautionary diagnosis tool. While the final detection requires further medical tests, such solution helps identify candidates for further investigation.

* InfraGraf is a patented Cognitive infrastructure automation platform that optimizes enterprise technology infrastructure investments. It diagnoses and predicts infrastructure failures. Need customized Machine Learning and Deep Learning solutions? Get in touch!

## Amazon Marketplace Link
The product can be found [here](https://aws.amazon.com/marketplace/pp)
