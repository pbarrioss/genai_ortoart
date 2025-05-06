# GEN AI PROJECT
Translating pictures in the operating room into art (impressionism to be specific)

Here I use a CycleGAN to "translate" or rather extract and apply features from an impressionist painting into pictures taken in the Operating Room.
The motivation for this was to create fun artistic images of my friends in the OR to distribute. 

While CycleGAN was not covered in class, it does use a lot of the principles we discussed: generators, discriminators, parameter setting, and fun latent space exploration. 

The datasets come from:
Painting dataset: kaggle
OR dataset: roboflow 

**The three things to install before running:
Import kagglehub
Import tensorflow.keras
Pip install Roboflow**

This model does run on a GPU and this is necessary, otherwise it will never generate images.  

I included here some sample images of what I was able to create using 100 epochs for easier visualization. 

![dd40ca76-bba8-4333-a741-315e08b5472f](https://github.com/user-attachments/assets/2e4105e4-5203-412c-9154-7d9a4c81d065)
![f0e81d55-fe65-4c94-90b1-c44750040313](https://github.com/user-attachments/assets/ed2eb972-743d-4ad2-8ca1-ac1138264696)
![9903f738-590f-477a-9d3f-893cdf1b280e](https://github.com/user-attachments/assets/a28c8ecb-0f64-4783-9587-da4029f5e4aa)

**Latent Space Exploration **
![cd4294da-55a4-4451-9525-fba370c56e53](https://github.com/user-attachments/assets/78f258fb-dbf9-4216-958b-086222af3434)
![33a0442e-1d04-43a7-a0a3-b228e0f5439f](https://github.com/user-attachments/assets/5baa70c4-7cae-40c9-8c68-ef37d884b094)
![f0e81d55-fe65-4c94-90b1-c44750040313](https://github.com/user-attachments/assets/66618d2c-1837-4cb3-95ad-bc5e5c10163e)

**I realize that really two things can happen - you can put in mages to be chagned into art, or images to be changed into "OR-esque" pictures**'
So I played around with some images of my own to turn them into impressionism art

![582031c3-1589-4bc6-baa5-4baca7d273c7](https://github.com/user-attachments/assets/83e5df44-6667-4263-bd75-8dae59e00dca)
![9f0f9ca5-8117-4689-ad0d-386560e665ce](https://github.com/user-attachments/assets/806ef286-b06f-43a7-af00-ae47165e7af4)

**CONCLUSION**
This was a lot of fun and I learned a lot, but my friends will not want these pictures - at least not without more training. 
