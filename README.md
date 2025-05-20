This is the official Repository of RadCLIP: RadCLIP: Enhancing Radiologic Image Analysis Through Contrastive Language–Image Pretraining

# RadCLIP
RadCLIP is trained on over 1.15 million 2D radiologic image–text pairs and 52,766 3D volumetric pairs spanning X-ray, CT, and MRI, drawn from 14 public collections.

![Dataset](https://github.com/user-attachments/assets/cda8e9db-18f1-46c2-87b8-042a6ab98de1)

Our architecture builds on a dual-encoder CLIP framework: a frozen text encoder paired with a fine-tuned 2D image encoder, optimized with an InfoNCE contrastive loss to align image–text embeddings. Volumetric studies are handled by a lightweight, multi-head self-attention slice-pooling adapter that aggregates 2D slice features into a unified 3D representation—avoiding costly 3D convolutions. 

![RadCLIP](https://github.com/user-attachments/assets/0ee97a98-dc83-4272-bbe2-052235d8a3ac)

## 🔗 Pre-trained Model Links

All RadCLIP checkpoints are hosted on Hugging Face:

**RadCLIP Model Weights**  : https://huggingface.co/zluvolyote/RadCLIP  

