# Your First Line of Code
-----
1. Click on **Create** > Under **Start From Template** > Open **Help Desk** app
![image](https://user-images.githubusercontent.com/20516321/133563344-d6a27722-4a20-4d8d-9872-f8f38d257ff2.png)

2. Name it as **RRITEC helpdesk** > click on **create** 
![image](https://user-images.githubusercontent.com/20516321/133564286-173c0684-8e72-4237-9e38-dd7cb4251a3a.png)


3. Click on **Allow** > Click on **OpenApp**
4. Click on **Preview the app** > Click on **Login as a Help Desk Admin** > observe the error msg
![image](https://user-images.githubusercontent.com/20516321/133564021-d4ca4881-a40f-4995-8cff-d58157eaf170.png)

5. To fix this error let us change code
6. Click on **app** > Select property as **OnStart**
![image](https://user-images.githubusercontent.com/20516321/133564542-9a85f04f-3f2a-43bf-b565-045217cef0bb.png)

7. Add M365 developer account to **AdminList**  
    
                  ClearCollect(AdminList,"MariaC@contoso.com","JimG@contoso.com","ScottK@contoso.com","NancyA@contoso.com","ThomasA@contoso.com","YvonneM@contoso.com","mylaramreddy@mylaramreddy.onmicrosoft.com")
      
8. Click on app **...** > Click on **Run onStart** > **Save** it
9. Open the app > Click on **Login as a Help Desk Admin** > now we will be able to login
![image](https://user-images.githubusercontent.com/20516321/133566839-ec417fa7-a49b-4c90-b98e-21ce40061131.png)

 
