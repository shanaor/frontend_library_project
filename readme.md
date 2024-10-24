# <u> Library management Application</u>

**This project is for library stock and customer management**

**<u>This is the frontend HTML and Javascript for Page design and page logic</u>**

The backend server python script logic is in here -->>> [Github backend](https://github.com/shanaor/backhand_library_project) <br>
[[For Eyal: here is the storelink: [-->> Store link to start project checking <<----](https://shanaor.github.io/frontend_library_project/) ]]

<br> ***Important!!!!*** I used HTML Input restrictions which made some codes in the backend unnecessary , but I left them in because at thier base they are correct as part of correct server actions for a library. 

 ***Also Important!!!!*** The style of how I wrote the cards with inconsistent design is ON PURPOSE. it's to create unique attributes to different functions so they would be easier to recognize by it (assuming that it would create more alertness of the user and therefore less mistakes)

## <br><u>It has the following features:</u>

1. add customer
2. Deactivate customer
3. Add book
4. Deactivate book
5. Change book quantity
6. Loan a book
7. Return loans
8. Get notifications for late return
9. Search existing customers (deactivated and activated)
10. Search existing books (deactivated and activated)
11. Get a list of late loans
12. Get a list of all Returned books
13. list of existing loans including date and time
14. Get store stock, Customer and loan Statistics
15. Get Log information about actions performed in the application by the users sorted by dates
16. And Reset Data to 5 automatic customers and books

### <u>additional features in frontend style design</u>
This application uses Bootstrap Link import to make a more responsive design and specifically builds 3 attributes of the site: 
- The carousel
- To make the warning alert for the late loans
- The information input cards and windows in the result DIV.

***And Axios Link import was used as well***
_____

## The "old fashion" frontend look
I have yet to explore bootstrap all the way and be aware of its great options so I used the first option CHATGPT offered. <br>
So the project complete the requirments asked of me for this Project but by using bootstraps tht look like from a 90's Website :o). <br>
I did learn some interesting things about HTML tags along the way so that was Fun. 8) 

## The Late Loan Alert
In the beginning - under The API Call function there is a call for the Index API to extract an Alert in case the Server found a late loan. Please be aware. 

## HTML Structure

Select Menus were used to allow minimizing of the Website space, and are present by Functions that switch between the different subjects. 

Some input windows were left just so the website would have some volume to it, and at the bottom there is the Result Div to show User action result responses. 

### <u> Buttons </u> 
A person may wonder if Filter search option is available in the site then why did I make the Button that show Data result. <br>
Simple answer is - convenience. <br>
 To allow quick Result when necessary. 



## NOTE ## 

I am aware about the Style in line VSC remark. this is because in a lot of places I used inline styling because I wanted to change sometimes just an individual letter or sentence. <br> so making a CSS for each one would have been HELL ON EARTH.





<br><br>
Thank you for taking interest in the Project,
For any inquiry you can reach me at ppol51377@gmail.com