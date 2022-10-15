# CLIPLSD: Project for EPFL Course Computational Photography: CS-413

Repository for CLIP-supervised GAN-based Image Editing.

`cliplsd.py` contrains all training code for the project.

The `notebooks` folder contains all experiment notebooks.

### Streamlit apps

A streamlit app is provided to view the trained directions depending on the chosen parameters.

```
streamlit run 1D_visualization.py
```

Using this app you can view the edits made by the directions found by the model.

For more information check out the report pdf.

## Some Results

<img width="921" alt="Screenshot 2022-10-15 at 09 46 36" src="https://user-images.githubusercontent.com/73786209/195975729-4ca641dd-8a7d-48fe-8fc6-6d33340083ec.png">
<img width="865" alt="Screenshot 2022-10-15 at 09 46 47" src="https://user-images.githubusercontent.com/73786209/195975736-9b809260-d55a-498c-980c-5ce4cc75dc06.png">
<img width="865" alt="Screenshot 2022-10-15 at 09 46 53" src="https://user-images.githubusercontent.com/73786209/195975740-6b83c45c-28f0-4ecd-8689-86629a9642b8.png">

## Acknowledgment

This project builds on top of [**Optimizing Latent Space Directions For GAN-based Local Image Editing**](https://github.com/IVRL/LELSD)
