*************Webstorage*************
1. What's web storage?
   
   Users able to store data locally with their browsers.

2. What are the types of web storages?
   
   1. cookies
   2. local storage
   3. session storage
   
   1. cookies: 
        
        Store data that has to be sent back to the server with subsequent requests.
        Its expiration varies based on the type and the expiration duration can be set from
        either server-side or client-side. But normally server side.
        
        Cookies are primarily for server-side reading.
        
        Store data less than 4KB.
        
        Cookies can be made secure by setting the httpOnly flag as ture. As we do so, it will prevent
        client side access to that cookie.
        
    2. Local storage:
       
       Maximum amount of data can be stored amoung others with no expiration date. Data will be deleted when close the browser 
       but it will be existing on the user's browser the next day, month and year. 
       It will get cleared by clearing browser cache or JavaScript.
     
    3. Session storage:
    
       Store data for one session only. It will be deleted when we close the browser's tap.
       Data is never transferred to the server. Storage limit is larger than a cookie at least 5MB.

3. What are advantage of web storage?

   1. More secure.
   2. Can store large amount of data without affecting website performance.
    
    

   


