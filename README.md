# BookingController

BookingController is an OK code but it needs some refactoring such as:
1. Return reponse should be json with reponse status code (200,500 etc. if this is an API)
2. Implementing middle ware such as Laravel Passwport or JWT for security purposes, "$user_id" is not declared on BookingController line 38 and line 110.I also commented on some lines where variable is assigned but value never used.
3. Implementing try catch so we can determine and properly return the error message to the front end.
4. ADMIN_ROLE_ID and SUPERADMIN_ROLE_ID should be much better if it's stored in database for much better flexibility of the system for example if we want to add different roles.
5. In distanceFeed function use of if else statement multiple times make it lengthy we can also do this through form data validation.

