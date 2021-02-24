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

**The result of the first part is a randomly generated image with a resolution of `1024x1024.`**

![](https://github.com/MatthewRomanishin/malivar_task/blob/main/examples/first_face_300x300.png)

You can run last cell in the part "Creating a head" as many times as you like until the head you like is generated.

Keep running cells one by one!

In the output of the last cell of the second part, you can change the parameters of the face using the sliders. 
Do not forget to click on the "Generate" button to see the result and automatically save the changes for future work!

**The result of the second part is a modified image from the first part**

For example:

**Gender**

![](https://github.com/MatthewRomanishin/malivar_task/blob/main/examples/gender_300x300.png)

**Age**

![](https://github.com/MatthewRomanishin/malivar_task/blob/main/examples/age_300x300.png)

**Smile**

![](https://github.com/MatthewRomanishin/malivar_task/blob/main/examples/smile_300x300.png)

### We got to the last part of my job

***Please pay attention to this instruction***

![](https://github.com/MatthewRomanishin/malivar_task/blob/main/examples/instruction.JPG)

And keep running cells.

You will see the 3d model of the head that you created. With the mouse you can make different turns of the head.

![](https://github.com/MatthewRomanishin/malivar_task/blob/main/examples/3d_head.JPG)









