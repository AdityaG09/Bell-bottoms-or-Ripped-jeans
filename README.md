# Bell-bottoms-or-Ripped-jeans  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AdityaG09/Bell-bottoms-or-Ripped-jeans/blob/main/bell_bottom_or_ripped.ipynb)  
This a simple and fun little classifier I made which can classify between bell bottoms and ripped jeans. In the end, I used hooks functionality of PyTorch to generate Grad-CAM heatmaps and overlaid it on top of the original image. This gave me the opportunity to understand how the classifier worked under the hood.  
The notebook explains the steps and process in detail, so that it is easy to follow along.  
### Grad-CAM on Bell bottoms
<p align="left" width="100%">
    <img width="33%" src="https://github.com/AdityaG09/Bell-bottoms-or-Ripped-jeans/blob/main/heatmap_images/bell_bottom_sartorial.png"> 
    <img width="33%" src="https://github.com/AdityaG09/Bell-bottoms-or-Ripped-jeans/blob/main/heatmap_images/bell_bottom_women.png"> 
</p>

### Grad-CAM on Ripped jeans
<p align="left" width="100%">
    <img width="33%" src="https://github.com/AdityaG09/Bell-bottoms-or-Ripped-jeans/blob/main/heatmap_images/best_ripped_jean_casual.png"> 
    <img width="33%" src="https://github.com/AdityaG09/Bell-bottoms-or-Ripped-jeans/blob/main/heatmap_images/ripped_jeans_rough.png"> 
</p>  

We see how when making the prediction, the model focuses on the knees and the trouser leg area. This is pretty intuitive since the jeans are mostly ripped near the knee region, and bell bottoms have their signature bell shape in the trouser leg area.
