# Project Information
<p><b><h6>Name Project :</b>Jdatecustomize (تاریخ جلالی ویژه به زبان php)</p>
<p><b>Last version  :</b>1.0.0</p>
<p><b>Last updated :</b> 17/10/2020</p>
<p><b>Programming language :</b> PHP</p>
<p><b>Company name : </b><a target="_black" href="https://sunnyweb.ir">sunnyweb</a></p></h6>
<h4>اگر می خواهید از تاریخ و زمان به صورت سفارسی در کشوره ای جلالی استفاده کنید این گزینه ویژه در دسترس شما می باشد</h4>
سعی شده تمام توابع مورد نیاز به صورت فانکشن برای برنامه نویسان قرار داده شود تا بتوانند به صورت احتصاصی برروی زمان به صورت جلالی مدیریت داشته باشند 
 <h5>روش استفاده</h5> 
  <br>
  <code>include_once 'jdatecu.php';</code>
  <br>
  <h5>توابع به همراه نمونه</h5>
<code>
  irtime();
</code>
<br>
<code>
  jdate("Y/m/d", 'زمان شما که می خواهید تبدیل شود به جلالی');
</code>
<br>
<code>
  jmaketime(0,0,0,jdate("m"),1,jdate("Y"));
</code>
<br>

<br>
<code>
 mstart($month, $day, $year);
</code>

<br>
<code>
lastday($month, $day, $year);
</code>

<br>
<code>
days_of_year($jmonth, $jday, $jyear);
</code>

<br>
<code>
monthnumber($month);
</code>

<br>
<code>
Num2Fa($srting);
</code>

<br>
<code>
is_kabise($year);
</code>

<br>
<code>
jcheckdate($month, $day, $year);
</code>

<br>
<code>
jtime();
</code>

<br>
<code>
jgetdate($timestamp = "");
</code>


<br>
<code>
gregorian_to_jalali($g_y, $g_m, $g_d);
</code>

<br>
<code>
jalali_to_gregorian($j_y, $j_m, $j_d);
</code>

# Contacts
<ul>
<li>   Author      :   تیم برنامه نویسی سانی وب
<li>   Linkedin    :   https://ir.linkedin.com/in/joshani
<li>   E-Mail      :   mr.mtwoj@gmail.com
<li>   Website     :   www.sunnyweb.ir
<li>   Twitter     :   <a href="https://twitter.com/MrMtwoj">@mrmtwoj</a>
</ul>
