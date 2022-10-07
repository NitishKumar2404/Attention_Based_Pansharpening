# Multi-Patch Self-Attention Network for Pansharpening

## Description

This repository contains the code for Attention-Based Deep Learning model for performing fusion of Optical Remote Sensing Images (Low Resolution Multi-Spectral Image (LRMS) and Panchromatic image (PAN)) to generate a High Resolution Multi-Spectral Image (HRMS)

## Dataset 

The dataset IKONOS and LANDSAT-8 cannot be made public without the permission of ESA Archives.

## Attention Model

Motivated by the recent success of self-attention mechanisms in computer vision tasks, self-attention architecture, for pansharpening that computes band-wise attention. A further improvement is proposed in the attention network by introducing a \textit{Multi-Patch Attention} mechanism, which operates on non-overlapping, local patches of the image. Our model is successful in infusing relevant local details from the Panchromatic image while preserving the spectral integrity of the MS image.

## Metrics

We use the following No Reference Metrics to compute quality of the results: 

 - SAM (Spectral Angle Mapper)
 - SCC (Spatial Correlation Coefficient)
 - PSNR (Peak Signal-Noise Ratio)
 - UQI (Universal Quality Index)
 - SSIM (Structual Similarity Index Measurement)
 
 ## Link To Work
 
 https://www.techrxiv.org/articles/preprint/Pansformers_Transformer-Based_Self-Attention_Network_for_Pansharpening/17153228
 
 ## Contributors
 
 - Nitish Kumar Murali
 
 - Nithin G R
