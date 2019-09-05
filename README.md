<!DOCTYPE html>
<html>
<head>
<title> my task </title>
</head>
<style>
input[type=text], select {
  width: 50%;
  padding: 12px 20px;
  margin: 10px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}
input[type=message], {
   width: 50%;
  padding: 100px 20px;
  margin: 10px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}
input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 50px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: center;
  
input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
<body>
<h1 align="center"> <span style="color:black;background-color:gray;"> AYOMIDE RESUME </span> </h1>
<h2 align="center"> <span style="color:black;background-color:gray;"> AYOOLA AYOMIDE ABRAHAM </span>
</h2>
<hr />
<p> I am a committed,diligent and hardworking person. Perfection is the watchword and I have good interpersonal and communication skills. I aim to be a value provider, focusing at achieving maximum excellence, and also aim to impact and solve myriad problems encountered by today's humanity. </p>
<br />
<h6> <strong> <span style="color:green;background-color:gray;"> CONTACT INFORMATION</strong></span></h6>
<table>
<ul>
<p>AYOOLA AYOMIDE ABRAHAM</p>
<p>13 owolabi street </p>
<p>ibadan oyo state</p>
<p>09064903399</p>
<p>Heywhy154@gmail.com</p>
</ul>
</table>
<hr />
              <!-- the CV details begin --->
<h2> <span style="color:green;background-color:gray;"> PERSONAL PROFILE </span></h2>
<table>
<ul>
<li>  Date of birth: 15th February 1998 </li>
<li>  Religion: Christian </li>
<li>  State of Origin: Oyo state </li>
<li>  Sex : Male </li>
<li> Marital status: Single </li>
</ul>
</table>
<hr />
<h2> <span style="color:green;background-color:gray;"> SKILLS </span> </h2>
<table>
<ul>
<li>Software tools- Microsoft office, CorelDRAW. </li>
<li> Web Applications. </li>
<li> Social media management. </li>
<li> Content management. </li>
<li> infographics and design </li>
 </ul>
 </table>
<hr />
<h2> <span style ="color:green;background-color:gray;"> EXPERIENCE </span> </h2>
<p>
<strong>
DEMMY GLOBAL, OGBOMOSHO OYO STATE - <br /> IT Support /Social Media <br />
15th AUG 2017- PRESENT 
</strong>
</p>
<table> 
<ul>
<li> Design and implement social media strategy to align with company goals. </li>
<li> Edit, publish and share engaging content daily. </li>
<li> Monitor SEO and web traffic metrics </li>
<li> Communicate with followers, respond to messages and comments in a timely manner and monitor reviews. </li>
<li> Oversee social media accounts’ design (e.g. timeline cover, profile pictures) </li>
 </ul>
</table>
<hr />
<h2> <span style="color:green;background-color:gray;"> EDUCATION </span> </h2>
<table> 
<ul> 
<li>  University of Ilorin, Kwara  State, Nigeria.  Bachelor in Computer science (B.Sc. in view). </li>
<li> School Of Science Ogbomoso, Oyo State, Nigeria (2016).  West African senior school leaving certificate. </li>
<li> Bethel Baptist College, Oyo State, Nigeria (2010).  First school leaving certificate. </li>
</ul>
</table>
<hr />
<h2> <span style="color:green;background-color:gray;"> INTREST/HOBBIES </span></h2>
<table> 
<ul> 
<li> Coding </li>
<li> Surfing the Net </li>
<li> Reading </li>
<li> Writing </li>
</ul>
</table>
<hr />
<h2> <span style="color:green;background-color:gray;"> REFEREES </span> </h2>
<table>
<ul> 
<li>Engr. Aniebiet Udoh <br /> Mobil Company/Codehuz,Eket,Kwara State. <br /> 08134496448 </li>
<br />
<li> Stephen Gabriel Akpan <br /> Redford Computers,Ikeja,Lagos State. <br />07030308488 </li>
</ul>
</table>
             <!-- The CV details end --->
             <hr />
<br />
<h3 align="center"> <span style="color:white; background-color: gray"> CONTACT FORM </h3>
<br />
<br />
<div>
  <form action="/action_page.php">
    <label for="fname"> <span style="color:black; background-color: gray"> Full Name</label>
    <br />
    <input type="text" required id="fname" name="firstname" minlength="4" placeholder="input Your name..">

    <br />
    
     <label for="email"> <span style="color:black; background-color: gray">Email</label>
     <br />
    <input type="text" pattern="^([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x22([^\x0d\x22\x5c\x80-\xff]|\x5c[\x00-\x7f])*\x22)(\x2e([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x22([^\x0d\x22\x5c\x80-\xff]|\x5c[\x00-\x7f])*\x22))*\x40([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x5b([^\x0d\x5b-\x5d\x80-\xff]|\x5c[\x00-\x7f])*\x5d)(\x2e([^\x00-\x20\x22\x28\x29\x2c\x2e\x3a-\x3c\x3e\x40\x5b-\x5d\x7f-\xff]+|\x5b([^\x0d\x5b-\x5d\x80-\xff]|\x5c[\x00-\x7f])*\x5d))*$" title="Input a valid email adress." required id="email" name="" placeholder="input your email..">

    <br />

  <label for="Title"> <span style="color:black; background-color: gray">Title</label>
  <br />
    <input type="text" required id="Title" name="" placeholder="your title..">

    <br />

  <div class="row">
    <div class="col-25">
      <label for="message"> <span style="color:black; background-color: gray">Message</label>
    </div>
    <div class="col-75">
      <textarea required id="message" name="message" minlength="20" placeholder="Write something.." style="height:20px;  padding: 50px 250px;"></textarea>
    </div>
  </div>
        <br />
    </select>
  
    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>
 
