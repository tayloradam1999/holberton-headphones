# 0x04. Implement a design from scratch

> It is worth noting that for this project's readme, some of the links will not be accessible to everyone as some links point to my school's curriculum. These links are included for my project to be manually reviewed by a peer or instructor effectively and efficiently.  
  
In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.  
  
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.  
  
Here is the **final result**:  
![Final result](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210828%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210828T193530Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=db004833cd37ca36d40e77cbebcef4ace7138fbc89b07659639c9e6ad365fbce)  

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
