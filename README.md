# Self-supervised
Are Transformers More Suitable for Plant Disease Identification than Convolutional Neural Networks?
Recent studies suggest that the transformer-based architectures have made unprecedented achievements in various computer vision tasks, such as image classification, object detection, semantic segmentation, etc. However, as the de facto approach, convolutional neural networks (CNNs) have reigned for a decade in plant disease identification. Are transformers more suitable for plant disease identification than CNNs? To address this issue, this work aims to further investigate and evaluate whether it is feasible to trivially switch to transformers in plant disease identification tasks. A series of experiments were curated into three training strategies and implemented on two representative plant disease image datasets. Experimental results indicated that the vanilla transformer methods performed unsatisfactory performance when trained from scratch, and the two mainstream transfer learning-based approaches achieved better prediction performance but with little margin. It is encouraging that the self-supervision-based transformer methods outperform their CNN-based counterparts, which provides new insights for agricultural image processing. Importantly, this work revealed a model selection solution according to the experimental results and target datasets, and gained a better interpretation by visualizing the feature maps.
