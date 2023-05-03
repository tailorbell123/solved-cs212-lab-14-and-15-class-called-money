Download Link: https://assignmentchef.com/product/solved-cs212-lab-14-and-15-class-called-money
<br>
!”

<strong> </strong>

<ol>

 <li>Create a new class called Money, and include:</li>

</ol>

Instance variables for dollars (int) and cents (int).

A no-argument constructor which sets dollars and cents to zero.

A two-argument constructor accepting integer dollars and cents.

Get methods for dollars and cents.

A toString method which would print 6 dollars and 5 cents as:

$ 6.05

<em>(hint: to get the leading zero, you can take a substring of the last two characters of </em>

<em>“0”+the String values of cents.) </em>

compareTo and equals methods.




<ol start="2">

 <li>Write a small test program including statements like the following and others to test the methods in the class Money.</li>

</ol>







Money m1 = new Money();

Money m2 = new Money(6,5)

System.out.println(m1.getCents());

System.out.println(m2.getDollars());

System.out.println(m2);

System.out.println(m1.compareTo(m2));  System.out.println(m1.equals(m2));













<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/05/864.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/05/864.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>