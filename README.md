**Lung Cancer Detection Systems Using RIM Models**
**Authors**
**Prathisha S, Sivasupriya A, Varshini P, Varsha S**
_Department of Computer Science and Business Systems_  
_Knowledge Institute of Technology, Salem_

**Abstract**
Lung cancer is one of the most prevalent and deadly cancers worldwide, emphasizing the need for accurate early detection methods.  
This project introduces a **hybrid deep learning framework** for lung cancer detection from histopathological images. It uses an **ensemble of three CNN architectures** — **ResNet50**, **InceptionV3**, and **MobileNetV2** — to improve diagnostic accuracy.

**Each model contributes unique strengths:**
- **ResNet50** → Deep feature extraction through residual connections  
- **InceptionV3** → Multi-scale feature capture  
- **MobileNetV2** → Efficient processing of high-dimensional data  

The ensemble approach combines the predictions from all three models to produce a more reliable diagnosis.

## ⚙️ Methodology
1. **Image Preprocessing**  
   - Normalization  
   - Augmentation  
   - Resizing  

2. **Model Training**  
   - Each CNN model is trained independently.  
   - Weighted aggregation of predictions enhances accuracy.

3. **Evaluation Metrics**  
   - Accuracy  
   - Sensitivity  
   - Specificity  
   - F1-score  

The proposed ensemble model outperforms individual models, achieving robust and reliable classification between benign and malignant tissues.

**Technologies Used**
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy, Pandas, Matplotlib  
- Jupyter Notebook  
