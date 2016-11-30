# Jurnal Integration Library

This library contains a library to get access token for getting Jurnal user's data who's been installed your application. Every time user open the application, Jurnal will always generating new access token and send it to the application. Although the access token is new every time user open the app, <strong>the access token will always refers to the user that opens the app</strong>.

This Library contains object called <code>JurnalIntegration</code>

<h3>How To Use It:</h3>
  - Clone this script to your application
  - Use it in your application callback URL page that is registered in the developer center
  - If you install it properly, you will get access token by using <code>JurnalIntegration.get_access_token()</code>
  
<h3>JurnalIntegration Methods:</h3>
  - <code>get_access_token()</code><br>
    This method will get access token given from Jurnal to your application every time user open the application. The access token you get will be referred to user who is currently install and open your application. 
  
  


  
  





