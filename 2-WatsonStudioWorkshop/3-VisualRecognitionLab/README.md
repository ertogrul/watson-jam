# Lab: Creating Visual Recognition App on IBM Cloud
  

Returning to the agenda page?  [CLICK HERE](../README.md)  

Or maybe returning to the main page? [CLICK HERE](../../README.md)  

![image-w3-1](../../images/w3-1.png)
  
    
> IMPORTANT: The most important thing for you right now is to take your time and do not rush through the scripts. Rather, try to understand new concepts and let them sink in. You can finish the lab during the workshop but if you don't it's totally OK. You will be able to finish it later.  You can also continue with other labs that you find on the way. This is how any skill is built - by doing. 




# Task 1. Creating space in your organization on IBM Cloud account.

Prerequisites for this lab are:

- [ ] Existing **IBM Cloud** account 

- [ ] Started instance of **Watson Studio** on your **IBM Cloud** account 

IBM Cloud has several demonstration apps that you just need to find and start. Visual Recognition app will give you a chance to see how deployed model is connecting with cloud native www application. You can explore and tinker with it, this is what this app was created for :)  


> If you haven't registered to IBM Cloud or haven't started Watson Studio instance, please proceed to Preparation Lab.

When logged to IBM Cloud account navigate to Manage - Account menu in the top right corner of the screen.  

  
 ![image-w3-1-1](../../images/w3-1-1.png)      
  
  
Now click on Cloud Foundry orgs square in mid-screen.       
  
  
 ![image-w3-1-2](../../images/w3-1-2.png)    
  
Next click on your email address (visible on picture below) to enter your organisation (at this moment this is the only org on your IBM Cloud account).  

> Organisations and spaces are a way to organise applications based on cloud foundry. Oragnization can represent a department or a company. Within the organisation you can create many spaces. Space can represent apps, projects.

    
 ![image-w3-1-3](../../images/w3-1-3.png)         
    
In your organisation there is only one space: 'dev'. Create another space using 'Add Space' button on the upper right.  
    
 ![image-w3-1-4](../../images/w3-1-4.png)      
    
Select the region available and put a name for your space (for example: my-watson-app). Click the 'Save' button.     
> Note: write down the name of the region. You will need it while starting your app.  
    
 ![image-w3-1-5](../../images/w3-1-5.png)          
      
You should see a new space in a list, like on the screen below:    
      
 ![image-w3-1-6](../../images/w3-1-6.png)        
    
  
# Task 2. Creating Visual Recognition App on IBM Cloud    
  
Now when a space is created you will have a place to put your app in.         
Navigate to your dashboard on IBM Cloud. You can use first icon on the vertical menu on the left.      
    
 ![image-w3-2](../../images/w3-2.png)        
    
  

Right now Click on the search pane and write **"demo"**. You should see a 'Visual Recognition Node.js App' (among other things).    
      
 ![image-w3-3](../../images/w3-3.png)      
    
Click on that app. You will get to a page descibing what is exaclty started.    
      
> Note that first instance Visual Recognition service is free, so you don't have to worry about any charges. This rule applies to majority of services available on IBM Cloud. First service comes for free on a Lite plan.      
    
 ![image-w3-4](../../images/w3-4.png)      
      
Click 'Get Started'. You are redirected to a page creating your free Visual Recognition instance.      
    
  
 ![image-w3-5](../../images/w3-5.png)      
    
Now you need to choose a region that you previously written down during creation of new space.  
For a pricing plan ensure that you are on Lite. Then click 'Create' button.        
    
 ![image-w3-6](../../images/w3-6.png)      
    
You are redirected to your applications console page, click 'Deploy you App' button.    
      
 ![image-w3-7](../../images/w3-7.png)    
    

Select Cloud Foundry VM to deploy your app on (as on the screen below).    
    
 ![image-w3-8](../../images/w3-8.png)    
    
Now you need to click 'New' button in the part 'IBM Cloud API Key'. You will get a following pop up window:    
      
 ![image-w3-9](../../images/w3-9.png)      
      
You don't have to save this API key. For simplicity just click OK button and API key will be created for you.    
  

Leave memory allocation as it is.       
Now you need to choose again the region of your organization. When you do so, your spaces will show up like on the screen below. Choose newly created space and hit the 'Next' button.    
      
 ![image-w3-10](../../images/w3-10.png)      
      
Now you can see the final page before create an app. Ensure the region is region of your organisation and click 'Create'.    
      
 ![image-w3-11](../../images/w3-11.png)      
      
You are going back to applicatoion console page when a lot of things will happen automatically in the background. Wait 5-10 minutes. Finally status 'success' should be visible in the mid-screen as shown below. Click on the application link (black arrow on pic below).  
      
 ![image-w3-12](../../images/w3-12.png)      
   
 Now you can enjoy how the working model analyzes photos. You can upload your custom image and find our that there are many classifiers in the model that try to recognize what is presented on the picture.  
 Explore application console and application itself.  
  
      
 ![image-w3-14](../../images/w3-14.png)      
 
    
  
        
        
# End of Visual Recognition Lab