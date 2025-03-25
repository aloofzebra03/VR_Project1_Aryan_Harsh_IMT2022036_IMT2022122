## 🚀 How to Run the Code

1. Clone the repository and install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. Run `classification.ipynb` for both handcrafted and CNN-based classification.

3. Run `segmentation.ipynb` for traditional and U-Net-based segmentation.

4. All outputs and performance metrics are displayed in the respective notebooks.

---

## 📁 Directory Structure

The project follows a simple and organized structure:

```
├── classification_dataset/     # Contains images for classification (with_mask, without_mask)
├── MSFD/                       # Contains MSFD segmentation images and masks
│
├── classification.ipynb       # Jupyter notebook for classification (handcrafted + CNN)
├── segmentation.ipynb         # Jupyter notebook for segmentation (traditional + U-Net)
├── Readme.pdf                 # PDF version of the Readme with all required sections
├── requirements.txt           # All the packages needed to run the code
```

Each component is modularly separated for ease of experimentation and reproducibility.
