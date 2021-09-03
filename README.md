# 0x04. Implement a design from scratch

> It is worth noting that for this project's readme, some of the links will not be accessible to everyone as some links point to my school's curriculum. These links are included for my project to be manually reviewed by a peer or instructor effectively and efficiently.

> While working through this project and using dev tools every step of the way, I found that the VSCode extension ```Live Server``` was not always rendering exactly as expected. While implementing responsiveness in this project, I found that sometimes my view would be centered and sometimes my view would be off to the right or left with absolutely no changes to the code. The best way I found to keep my view consistant while developing this webpage was to ```right-click inspect``` in the middle of the **header** with the responsive dimensions of ```1240 x 850```. While testing for mobile responsiveness I used the dimensions of ```469 x 1163```. **Please consider grading in these dimensions as I tried for hours trying to figure out why I could not get a consistant view of my webpage in dev tools.**
  
In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.  
  
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.  
  
Here is the **final result**:  
  
![Final result](https://github.com/tayloradam1999/holberton-headphones/blob/main/readme_assets/finalresult.jpg)  

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens [here.](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip)

# Concepts
- [Implement a design](https://intranet.hbtn.io/concepts/726)

# Requirements
- you are not allowed to import external CSS framework (like Bootstrap)  
- you are not to use Javascript

## Task 0: Read and be familiar with Figma  

Create an account in [Figma](https://intranet.hbtn.io/rltoken/BQv9A-VghBpAgOlc-pVxQw) and open this [project](https://intranet.hbtn.io/rltoken/UWz3iOOx9ZSpwKRjLpYHoQ) and “Duplicate to your Drafts” to have access to all design details.  
If you can’t access to it, please find here the [Figma file](https://intranet.hbtn.io/rltoken/Ec1-9OpNim5R_yk0ZDV-_Q) 

**Important notes with Figma:**
- if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/JgZNK1n5wwp7vo9qRvs59Q) and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/HCSoboS1s9MLKdF1m8EBzQ)
- some values are in float - feel free to round them  

**For this task, please write an amazing README.md**

**Interaction notes:**
- the web page must switch to the mobile version when the screen width is 480px or less
- links hover/active: ```#FF6565```
- button hover/active: ```opacity: 0.9```
- max width of the content: 1000px centered in the page  
  
## Task 1: Header  
  
Building a web page the right way is not easy - except if you put in place strong foundations:
- reset CSS styling
- use variables
- simple/“as generic as you can” CSS selectors
- avoid using super specific CSS selectors as much as possible
- simple HTML structure - ```div``` containers are your friend!  

Last piece of advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to another way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.  

*Now, your turn!*

For this first task: **create the header/hero piece**  
  
Here is an archive of all assets needed: [images_0x04.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210828%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210828T193530Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=d0b3a829db5000bd4473f5bd0b511576c252e96fd14031931a70ecbbe8c8920e)  

**Desktop:**  
  
![Desktop Picture](https://github.com/tayloradam1999/holberton-headphones/blob/main/readme_assets/desktop.gif)  

**Mobile:**  
  
![Mobile Picture](https://github.com/tayloradam1999/holberton-headphones/blob/main/readme_assets/mobile.gif)  
  
## Task 2: "What we do..." section

Copy Files from the previous task  

For this second task: **create the "What we do..." section**  

In this section, you will need custom font icons. Here is the archive of it: [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210830%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210830T193032Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=0f2153c7ad36669ea7585e201d00495de1c107b0d3251ae66d08adb5f53a3013). Inside you will find a demo page on how to use it.  

**Important:** Try to build as generic as you can... you will probably need some components in the next section.  

## Task 3: "Our results" section  

Copy files from the previous task.  

For this third task: **create the "Our results" section**

Now you can reuse components from the previous task!

## Task 4: Contact us  

Copy files from the previous task.  

A good landing page always has a contact form.  

You are free to add any animations and/or constraints on fields.  