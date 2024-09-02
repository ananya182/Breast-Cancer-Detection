# Breast-Cancer-Detection
Breast cancer is among the most prevalent cancers, and screening mammography plays a crucial role
in early detection. Mammograms, which are essentially X-rays of the breast, serve as the primary
tool for radiologists to identify malignant tissues. Typically, mammograms are of dimensions 4k×4k,
comprising X-rays captured from two perspectives: side-view (MLO-view) and top-view (CC-view).
While Deep Neural Networks (DNNs) have shown promise in classifying malignancy in cancers,
their integration into medical practice faces challenges, notably in terms of model explainability.
Despite achieving commendable results in classification tasks, these models cannot often explain/find
the regions contributing to their predictions. To bridge this gap and foster trust among clinicians,
it becomes imperative for models to not only classify but also localize cancerous regions within the
mammograms. Object detection emerges as a viable solution to this problem, allowing models to
draw bounding boxes around areas indicative of tumors.

In this project, I have trained a deep neural network for object detection in breast cancer screening. 
