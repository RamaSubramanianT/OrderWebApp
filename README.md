# Sales Order Web Application
 <h4>This is a Asp.Net Web App that features Order function.</h4>
<div style="display: inline-block;">
    <img alt="C#" src="https://img.shields.io/badge/C%23-blue?style=for-the-badge&logo=C%23">
    <img alt="ASP.NET" src="https://img.shields.io/badge/Asp.Net-purple?style=for-the-badge&logo=.net">
    <img alt="Dapper" src="https://img.shields.io/badge/Dapper-green?style=for-the-badge">
</div>
 <h5>Functions</h5>
 <ul>
  <li>Select</li>
  <li>Update</li>
  <li>Delete</li>
  <li>Create</li>
 </ul>

 <p>So this is a web application developed using Asp.Net, Dapper. Using Dapper we managed to communicate with Sql Server and execute sql commands. While we used Model-View-Controller way to develop a web application, where each controller do a different action, like insert controller contains action method that help us insert data from web app to sql.</p>


<h5>These are some features we incorporated in this application</h5>
<h5>Features</h5>
 <ul>
  <li>Login and logout: CookieAuthentication</li>
  <li>Cache: OutputCache and ResponseCache</li>
  <li>View Validation Attributes like: Required, string length, range()</li>
  <li>Route Attribute</li>
  <li>Bootstrap for CSS</li>
  <li>Mobile Responsive</li>
  <li>Logging: Using Serilog</li>
 </ul>

# Working
<h3>Login Page</h3>

![image](https://github.com/RamaSubramanianT/OrderWebApp/assets/109201625/8ce42f17-6ea6-48c0-85bc-701909da108e)

<hr>
<h3>Index Page</h3>
<p>This page shows all the items present in Orders Table</p>

![image](https://github.com/RamaSubramanianT/OrderWebApp/assets/109201625/072c380d-f643-4279-9b99-5d6f7e0b6a37)

<hr>
<h3>Update Page</h3>

![image](https://github.com/RamaSubramanianT/OrderWebApp/assets/109201625/bffa4718-c17f-4ad9-aea2-4425c769d6b2)

<hr>
<h3>Delete Page</h3>

![image](https://github.com/RamaSubramanianT/OrderWebApp/assets/109201625/7b2c26a5-c809-4e01-986c-616b267e701e)

<hr>
<h3>Insert Page</h3>

![image](https://github.com/RamaSubramanianT/OrderWebApp/assets/109201625/d3a2d52c-bfe3-4004-bebe-4cb5c4594910)

<hr>
<h3>Attribute Validation</h3>

![image](https://github.com/RamaSubramanianT/SalesOrder/assets/109201625/0370b7f5-d74a-42d0-b5f9-8c7443dc5dfb) ![image](https://github.com/RamaSubramanianT/SalesOrder/assets/109201625/7d2e4459-fada-4431-9e86-571ab4103970) 

<p>All the fields are validated, no empty value can be passed in any of the input field. Minimum and maximum length are set in product id field, in orderid value greater than 100 is invalid. Password is set to be 8 alphanumeric long and many more validation are done. Error messages will be displayed below the input field if any condition is violated. If a value is not present in Sql database then <b>"No Record Found"</b> is shown.</p>
<hr>

<h3>Log</h3>

![image](https://github.com/RamaSubramanianT/SalesOrder/assets/109201625/be4982e9-f757-45a5-a5b6-5feb4a1ea6c2)

<p>Using Serilog, every Event, Error and Exception is recorded in console and saved in log file.</p>



# Working Process
<p>We use Asp.Net MVC Web App to develop this application, here controller contains action methods which is called when client(web browser) sends a request to server, in response the server will send the contents, this content are mainly webpages which is present in Views and process the logic in the action method.</p>



©️ SalesOrder 2024
