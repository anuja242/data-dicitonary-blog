I am happy to share my very first blog post on SAP ABAP Programming. In this blog post you will learn how to create package and how to write your first program. This blog post based on classic development in SAP GUI.

How to Create Package
Once you login to the system, below screen will be open. On the left side of the screen there is command field. You can enter transaction code to go to any task of SAP application.

SE80 and SE38 are transaction code for ABAP editor.

Follow the below steps to create package.

Step 1: Enter SE80 transaction code in command field and press Enter.

<img width="153" alt="1" src="https://user-images.githubusercontent.com/64360066/184807182-5e6aaefb-f5c9-4bd3-b17c-60643cd44065.png">


Step 2: Select package from the drop-down list.

 
<img width="301" alt="2" src="https://user-images.githubusercontent.com/64360066/184807199-7b71ff8a-e4d3-4f22-a7a5-b42fe5dfcdad.png">



Step 3: Enter package name and press Enter.

 <img width="301" alt="3" src="https://user-images.githubusercontent.com/64360066/184807240-10b2b126-364d-43ea-bdaa-a8def1a2a7ec.png">



 

Step 4: It will prompt you to create the package if the package with the same name is not present. Click on Yes.

 
<img width="301" alt="4" src="https://user-images.githubusercontent.com/64360066/184807273-ac55481e-7e2d-4b50-bfcb-07174c38653f.png">



Step 5: Give short description and press enter and package is created.

 <img width="301" alt="5" src="https://user-images.githubusercontent.com/64360066/184807291-b0c33b53-e2fe-4a23-a0a4-c485b1f0aa48.png">


How to write program
 

Step 1: Once the package is created, right click on the package name. You will get the below options.

 

<img width="301" alt="6" src="https://user-images.githubusercontent.com/64360066/184807328-e233c4ce-64f0-4db8-b246-e28b3eab9a23.png">


 

Step 2: Click on Create option. Once you click on it you will get options. Select Program option.

 
<img width="301" alt="7" src="https://user-images.githubusercontent.com/64360066/184807341-52e621e7-a0e3-45ea-a666-3ca3cf8c2e04.png">



 

Step 3: Give the program name. Program name should start with Z or Y.

 
<img width="301" alt="8" src="https://user-images.githubusercontent.com/64360066/184807366-e736b5e1-0f26-42eb-8257-39b0aa86d425.png">



 

Step 4: Save it in your package. Once you save it you will get below screen. Here you can write your code.



Program to print Text
 

There is a keyword WRITE to print a text on output screen.

Syntax: Write ‘This is my first program’.

Write: It is a keyword to print text on output screen.

Whatever the text that we want to print on output screen must be inside the single quotation mark.

The statement is closed with period(.).

Note: Each statement must be closed with period(.).

 

<img width="301" alt="9" src="https://user-images.githubusercontent.com/64360066/184807537-80cb9318-a024-45c5-b77f-a16326390036.png">


 

Once you write your code, you can check your code whether it is syntactically correct or not.

To check click on check button which is shown in below image.

 

![image](https://user-images.githubusercontent.com/64360066/184807626-5740096a-f09c-4ec3-96f1-dd0ecb25b231.png)


 

Once you click on it will show you the error if it is present. If not, you will get the message like No syntax errors found in report.


![image](https://user-images.githubusercontent.com/64360066/184807649-d61b2b00-d175-4ab2-b103-411c0060aeab.png)

 

Then you have to activate your program. To activate this, click on activate button.

 
![image](https://user-images.githubusercontent.com/64360066/184807674-d73bcd3f-b216-4546-9e47-00b80efd9705.png)



Once your program is activated you can execute your program. Click on execute to run the program.

Note: Any changes if you done in your program then first you have to activate the program then run it. If the program is inactive then you will not be able to run your program. You can see that status just besides the report name.

 

![image](https://user-images.githubusercontent.com/64360066/184807706-cd160675-52ff-4208-a750-469ba0c760de.png)


 

Once you execute it, you will get the output.

 

![image](https://user-images.githubusercontent.com/64360066/184807727-8e383958-a3fa-41e8-bf63-4a93c601ecf6.png)


 

Here you have completed the first step into your learning SAP ABAP programming journey. I hope this blog post helped you as beginner.

As we continue to learn more, I will use this first blog post to link all the parts of this series.
