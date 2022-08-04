<h2><b><p>Functionality Testing for e-commerce website Amazon </p><b></h2>
<p>Automation script designed using Selenium webdriver, TestNG, and Java using the below concepts : </p>
<li>Page Objects to organize the methods on how to interact with the elements on the particular page</li>
<li>Wrappers for commonly used Selenium WebDriver functions</li>
<li>Actions classes grouping up commonly used methods, so tests are easier to create</li>
<li>Plain Ole Java Objects (pojos) to gather up and group together parameters of test objects, so we can pass one object into a method, instead of five or six parameters.</li><br/>
The directory structure:
<br />
<b>src/test/java</b><br />
<ul>
<li>actions</li>
<ul>
<li>OrderActions</li>
</ul>
<li>base</li>
<ul>
<li>LoadProperties</li>
</ul>
<li>enums</li>
<ul>
<li>Products</li>
<li>Url</li>
</ul>
<li>pages</li>
<ul>
<li>HomePage</li>
<li>SignInPage</li>
<li>ProductPage</li>
<li>ShoppingCartPage</li>
<li>ShoppingCartReviewPage</li>
</ul>
<li>pojo</li>
<ul>
<li>Book</a></li>
</ul>
<li>properties</li>
<ul>
<li>user.properties</li>
</ul>
<li>testcases</li>
<ul>
<li>PurchaseOrderTest</li>
</ul>
<li>utils</li>
<ul>
<li>CommonUtils</li>
<li>DriverUtils</li>
</ul>
</ul>
