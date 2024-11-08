This ressource pack is a test to create custom item in 3D

 using only custom model data in the last snapshot 24w45a.


You can open a gui by opening "Custom Item/assets/custom_item/python/gui.py" to create your model.

You can also convert a minecraft model using "Custom Item/assets/custom_item/python/conversion.py" but you have to enter texture and color yourself in the python code. I keep an exemple "egg.json" for testing purposis.

Exemple:
![2024-11-08_18 29 16](https://github.com/user-attachments/assets/1925cfef-a60f-40c3-b854-711f94e2e056)

![2024-11-08_17 34 03](https://github.com/user-attachments/assets/cc1834fd-995b-40b5-985b-b21a2d63b5b4)

How it's working:
There is one model composed of 4096 models (16x16x16), each one being a pixel cube than can be activate/deactivate and change color depending of a custom model data value.
