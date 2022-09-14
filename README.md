# Majimazuri_School_Management_System
This School management system was built for a local school to help in keenping track and maintaining records. Some features include:
1. Keeping track of the attendance and pulling up the records by teachers for their classes.
2. Video conferencing tool to reduce dependancy on external tools and save money.
3. Teachers can directly upload students marks and students can register complains incase of missing marks
4. Teachers can apply for leave and the admin can either approve or deny their requests.
5. Visualizations in terms of graphs for the admin to understand general distributions like teachers vs students or number of students per class


<h2>Installation Steps : </h2>

<p>Project Dependency :</p>
<pre>
pip install requests
pip install Django
pip install mysql-client
pip install mysqlclient
</pre>
<hr>
<ul>
<ol>
Run Migration Command 
<pre>
python manage.py makemigrations
python manage.py migrate
</pre>
 <ul>     
<li>In login_page.html Replace <pre>CAPTCHA_CLIENT_KEY</pre> with Captcha Client Side Key</li>
<li>In views.py Replace <pre>CAPTCHA_SERVER_KEY</pre> with Captcha SERVER Side Key</li>
<li>For Captcha Key Visit <a href="https://www.google.com/recaptcha/intro/v3.html">https://www.google.com/recaptcha/intro/v3.html</a></li>
</ul>
</ol>
<ol>
 <li>Run Project python runserver</li>
</ol>
</ul>
<ol><h2>Technologies used</h2>
 <li>Django</li>
 <li>ADMINLTE - Frontend content (built on Bootstrap 5)</li>
 <li>SQL Database</li>
</ol
<hr>
<hr>

