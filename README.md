# work

# 1. brief demo
training the model to recognize glasses wearing glasses vs not wearing glasses

model sharable link: https://teachablemachine.withgoogle.com/models/SbbYTuWnK/

(ignore the text under "Teachable Machine". I forgot to edit the index.html)

![06b94589e48b81d5ea9d91cf61ea2979](https://user-images.githubusercontent.com/60904107/214723545-88582ccf-0853-4aaa-b771-01d762db204f.gif)


# 2. gesture recognition
middle finger

as the middle finger extends the footage becomes colored. when it is closed it is gray.

![a1d109db309d00128a549c2fa454c918](https://user-images.githubusercontent.com/60904107/214728961-722b0d39-320d-4695-a251-977def48c6e5.gif)

As you can see on line 39, the distance bwtween the middle finger mcp and middle finger tip is taken.

then on line 50 we apply a filter if a threshold is met
![Screenshot 2023-01-25 at 7 47 54 PM](https://user-images.githubusercontent.com/60904107/214729194-7e106eae-2fc9-4465-ad7d-8e44bb937f90.png)


---
# lab07-machine-learning

1. Create a brief demo with Teachable Machine
  - Go to https://teachablemachine.withgoogle.com/
  - Follow the instrcutions for an Image Project (standard image model)
  - Train a model to recognize something from your webcam
  - Export your model, upload it!
  - Work off off this base code: https://editor.p5js.org/kongsally/sketches/QlyiZmMNp
  - Copy the base code into this web editor for [p5.js](https://editor.p5js.org/)
  - Replace the trained model link in the base code with a link to your trained model.
  - Code some kind of visual that reacts to the output of your classifier! See https://p5js.org/reference/ for reference

2. Create a program that uses gesture recognition
  - https://editor.p5js.org/kongsally/sketches/I2HuS0w1T  

## Submission Instructions
- Create a pull request against this repo
- push your code and/or a link to a gif or video of your work
