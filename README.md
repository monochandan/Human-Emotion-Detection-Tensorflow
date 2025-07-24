# Human Emotion Detection

This project explores multiple convolutional architectures for detecting human emotions from facial expressions.

---
## Example Prediction After Training ResNet34 model for 60 epochs

<img width="996" height="390" alt="resnet_prediction" src="https://github.com/user-attachments/assets/3e22ffda-3c1e-4bee-bca1-d35c43b58969" />

## CNN (2 Conv2D)

- **20 Epochs**
<table>
  <tr>
    <td><img width="576" height="455" alt="Image" src="https://github.com/user-attachments/assets/99a5db43-891a-4b45-a0f1-d4994e1d1679" /></td>
    <td><img width="567" height="455" alt="Image" src="https://github.com/user-attachments/assets/36c503fd-e726-456e-89c8-a5269982c679" /></td>
  </tr>
   <tr>
    <td align="center">Accuracy over 20 epochs</td>
    <td align="center">Loss over 20 epochs</td>
  </tr>
</table>





[CUTMIX](https://arxiv.org/abs/1905.04899)

- **3 epochs**
<table>
<tr>
    <td><img width="576" height="455" alt="Image" src="https://github.com/user-attachments/assets/e3037d43-a33d-405b-a87a-0b50c60b5a3e" /></td>
    <td><img width="576" height="455" alt="Image" src="https://github.com/user-attachments/assets/83ffd56f-eb2e-4cbc-9716-4285c54a80c8" /></td>
  </tr>
   <tr>
    <td align="center">Accuracy: 3 epochs</td>
    <td align="center">Loss: 3 epochs</td>
  </tr>
</table>


- **20 epochs**

<table>
<tr>
    <td><img width="576" height="455" alt="Image" src="https://github.com/user-attachments/assets/c27757f6-c7f1-4f38-9d6e-54ef747dc39c" /></td>
    <td><img width="567" height="455" alt="Image" src="https://github.com/user-attachments/assets/d95a9c23-61c8-4294-ab5b-d91aeadf1940" /></td>
  </tr>
   <tr>
    <td align="center">Accuracy: 20 epochs</td>
    <td align="center">Loss: 20 epochs</td>
  </tr>
</table>




[ResNet](https://arxiv.org/pdf/1512.03385)

- **ResNet34 with 60 epochs**

<table>
<tr>
    <td><img width="567" height="455" alt="Image" src="https://github.com/user-attachments/assets/d9f8dd1c-3783-4076-9c97-6b0bd6ac1ce9" /></td>
    <td><img width="576" height="455" alt="Image" src="https://github.com/user-attachments/assets/83b1420f-d515-4ba1-90b3-2515b19fec3b" /></td>
  </tr>
   <tr>
    <td align="center">Accuracy: 60 epochs</td>
    <td align="center">Loss: 60 epochs</td>
  </tr>
</table>
  




