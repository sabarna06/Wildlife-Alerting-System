# Wildlife-Alerting-System
In the realm of computer vision, this project presents a comprehensive solution for image classification, specifically focusing on the detection of humans in wildlife areas and the identification of diverse animals. The models are carefully crafted to address unique challenges associated with human and animal detection in natural environments. The integration of both models is facilitated through the Gradio library, offering an intuitive and interactive interface for users.
# About the models and interface
Human Detection Model:
The human detection model is trained on a dataset specifically curated for wildlife scenarios. It leverages the MobileNetV2 architecture, a lightweight and efficient convolutional neural network (CNN). The model's pre-trained weights from the ImageNet dataset enable it to capture relevant features, while fine-tuning ensures adaptability to the challenges posed by wildlife environments.

Animal Detection Model:
The animal detection model also employs the MobileNetV2 architecture, benefiting from its real-time capabilities and strong performance in image classification tasks. Pre-trained on the ImageNet dataset, this model is capable of recognizing a wide array of animals. A carefully curated list of animal labels enhances the model's precision in identifying specific species.

Integrated Gradio Interface:
The Gradio library serves as the backbone for seamlessly combining both human and animal detection models into a unified interface. This interface allows users, including wildlife researchers, conservationists, and enthusiasts, to effortlessly upload images and receive instant feedback on the presence of humans and the identification of animals. The integration aims to democratize access to advanced computer vision capabilities and make them accessible to a broader audience.
Prerequisites:
Intel oneAPI Toolkit: Download and install the latest version of the Intel oneAPI Toolkit.

Python Environment: Set up a Python environment with the required packages.
Kaggle API Key: Obtain a Kaggle API key and upload it.
Integration with oneAPI AI Analytics Toolkit
Human Detection Model Optimization
Include oneDAL Library: Integrate the oneDAL library into the human detection model code. This involves importing oneDAL and updating the code to leverage its APIs.

Optimized Computations: Utilize oneDAL for low-level compute optimizations, enhancing the performance of key data processing tasks.

Parallel Processing with DPC++: Leverage the Data Parallel C++ (DPC++) programming model provided by oneAPI for parallel processing across CPUs, GPUs, and accelerators.

Memory Optimization: Implement memory optimization strategies supported by oneDAL, including efficient data layout, minimized data movement, and cache-friendly data structures
Benefits of Integration
Accelerated Processing: Enjoy accelerated data processing tasks, resulting in faster model execution.

Resource Optimization: Optimize resource usage, leading to improved performance without compromising accuracy.

Ease of Implementation: Seamless integration of oneDAL APIs provides a user-friendly solution for enhanced functionality.

Parallel Processing Capabilities: Leverage the parallel processing capabilities of oneDAL for efficient computation across diverse hardware architectures.
Conclusion
By integrating the InteloneAPI Analytics Toolkit, we aim to enhance the efficiency and performance of our human and animal detection models. The seamless incorporation of oneDAL's capabilities underscores our commitment to utilizing cutting-edge technologies for optimal predictive accuracy. This integration exemplifies our dedication to staying at the forefront of advancements in data analytics and ensuring that our models operate efficiently and effectively in real-world scenarios.

# PRESENTATION VIDEO

https://github.com/sabarna06/Wildlife-Alerting-System/assets/155043288/02364366-507d-44f7-ad31-4e0e816fb38a



