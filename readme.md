This project explores the application of Federated Learning (FL) for 3D brain tumor
segmentation using the U-Net architecture. With an emphasis on privacy preservation, the study
addresses challenges posed by non-identically distributed (non-IID) data across clients,
leveraging the Federated Personalization (FedPer) technique to improve performance. The
BraTS2020 dataset was utilized to train and validate the model, focusing on segmenting glioma
sub-regions: whole tumor , tumor core, and enhancing tumor . Comparative experiments were
conducted under centralized learning and federated learning paradigms, evaluating equal and
unequal data distribution scenarios. Results demonstrate that while centralized learning
provides strong baseline performance, FedPer significantly enhances segmentation outcomes in
non-IID data distributions, narrowing the performance gap between FL and centralized
learning. Future work involves analyzing client contributions to the global model and extending
the framework with TransUNet to capture global context for improved medical image
segmentation.
