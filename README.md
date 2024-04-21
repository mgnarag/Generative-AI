This is my attempt to fine-tune a stable diffusion model for my own dataset — my face. I used the pretrained model from https://huggingface.co/stabilityai/stable-diffusion-2. I only used 10 images for this activity; it can also work with 6, but 10 images provided better results. The following results are from my version 4 of **fast-DreamBooth.ipynb**. Please ignore fast-DreamBooth_5.ipynb for now.

**Results:**
Here are screenshots of the faces generated. According to my friends, my model correctly captured my glasses, nose, and side mustache. However, my facial shape is not quite there; it appears a little too chubby.

These two images looks like me inside a laboratory class. The shape of my face is really not there yet.
![Screenshot 2024-04-21 at 15 04 26](https://github.com/mgnarag/Generative-AI/assets/60250923/6651b4a6-6933-48b8-8486-a3199a4da189)
<img width="1440" alt="Screenshot 2024-04-21 at 15 04 46" src="https://github.com/mgnarag/Generative-AI/assets/60250923/690182db-6448-4ba9-b3a2-9ca6833da5f3">



**These three are by far, the closest to my actual face:**
<img width="1440" alt="Screenshot 2024-04-21 at 15 09 19" src="https://github.com/mgnarag/Generative-AI/assets/60250923/4702f85b-529c-4a7e-832c-dc29f644981f">
<img width="1440" alt="Screenshot 2024-04-21 at 15 09 57" src="https://github.com/mgnarag/Generative-AI/assets/60250923/60187339-1e10-48a1-ade0-ea645711d3ed">
<img width="1440" alt="Screenshot 2024-04-21 at 16 32 53" src="https://github.com/mgnarag/Generative-AI/assets/60250923/f2df489d-01a5-4e11-9503-15c8590e2bd4">


For the record, here are my training images. My caption for all the images is just "Jem", my nickname.
<img width="1439" alt="Screenshot 2024-04-22 at 07 13 03" src="https://github.com/mgnarag/Generative-AI/assets/60250923/a2146238-318a-47cc-a3a0-8346790fc213">
One reason why the shape of my face is _not there_ can perhaps be attributed to my training images. All of them are too different. In my version 5, I actually took 30 selfies with minimal pose changes and consistent background. It actually got my face correct but the skin tone is not there. 








