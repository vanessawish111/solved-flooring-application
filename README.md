Download Link: https://assignmentchef.com/product/solved-flooring-application
<br>



Developing a graphical user interface in programming is paramount to being successful in the business industry. This project incorporates GUI techniques with other tools that you have learned about in this class.

Here is your assignment: You work for a flooring company. They have asked you to be a part of their team because they need a computer programmer, analyst, and designer to aid them in tracking customer orders. Your skills will be needed in creating a GUI program that calculates the flooring cost and stores the order in the database.

The project has three components: an analysis and design document, the project code, and a user manual. The analysis and design document is due Week 4. The code and user manual are due in Week 7. It is suggested that you begin working on the code in Week 5, which should give you ample time to complete the project. You will find that the lessons and lab assignments will prepare you for the Course Project.

Guidelines

Your application must include at least three tabs. The user will choose wood flooring or carpet, enter the length and width of the floor, as well as the customer name and address. The application will compute the area of the floor and the cost of the flooring considering that wood floor is $20 per square foot and carpet is $10 per square foot. A summary should be displayed, either in a tab or another window, listing the customer name and address, floor selection, area, and cost. This information should also be stored in the MySQL database table. The program should validate that all information is entered and that the length and width are numeric values. Any numeric or currency values must be formatted appropriately when output. Recommendations for the components used for input are

·         radio buttons—flooring type (wood or carpet);

·         text fields—customer name, customer address, floor length, and floor width; and

·         buttons—calculate area, calculate cost, submit order, display order summary, display order list.

The MySQL database table is called flooring and has the following description.

<table border="0" cellpadding="0">

 <tbody>

  <tr>

   <td><strong>Field</strong></td>

   <td><strong>Type</strong></td>

  </tr>

  <tr>

   <td>CustomerName</td>

   <td>varchar(30)</td>

  </tr>

  <tr>

   <td>CustomerAddress</td>

   <td>varchar(50)</td>

  </tr>

  <tr>

   <td>FlooringType</td>

   <td>varchar(10)</td>

  </tr>

  <tr>

   <td>FloorArea</td>

   <td>double</td>

  </tr>

  <tr>

   <td>FloorCost</td>

   <td>double</td>

  </tr>

 </tbody>

</table>

In addition to entering new customer orders, your application should list all customer orders stored in the database. These will be viewed as a list, in a text area, and will not be updated by the user.


