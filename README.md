## **Intro**
I want to present my work to you.

### **The plan**
- Creating a head of a person that doesn’t exist (like [here](https://thispersondoesnotexist.com))
- Editing parameters of this head (age, gender, smile, etc.)
- Making some rotations (roll, yaw and pitch)

### **How I did it**
For creating and editing head I used [this](https://github.com/AmarSaini/Epoching_StyleGan2_Setup) work.
I thought it was a good idea to make a 3D head model for making some rotations. To implement this idea I used [3DDFA](https://github.com/3D-Face/3DDFA_V2).

## **How to use**

To run `malivar_task.ipynb` you need to save this notebook to your `Google Drive` and open with `Google Colab`.
All libraries required for stable work installing inside this notebook.

### The notebook is divided into 3 parts:
- Creating a head
- Changing facial attributes
- Creating 3D model and dataset with different poses

### **Let's start!**
It's very easy to use my work: just run cells one by one and watch the results.
The result of the first part is a randomly generated image with a resolution of `1024x1024.`

![](https://github.com/MatthewRomanishin/malivar_task/blob/main/examples/first_face.png)

You can run last cell in the part "Creating a head" as many times as you like until the head you like is generated.


