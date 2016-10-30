# Tribute-Page
This is my first time using github.Using codepen, I created a tribute page to Nnamdi Azikiwe (Former President of Nigeria)
I made use of HTML/CSS (first trial in web building)

this is my HTML code 

<div class="container">
  <div class="jumbotron">
    <div class="row">
      <div class="col-xs-14">
        <h1 class="text-center">Dr. Nnamdi Azikiwe</h1>
        <h2 class="text-center"><em>First Ever President of Nigeria</em></h2>
        <img class="thumbnail" src="https://dates4usblog.files.wordpress.com/2014/10/nnamdi-azikiwe.jpg"></div>
        <div class="col-xs-12 col-sm-10 col-sm-offset-1 col-md-8 col-md-offset-2">
          <h3>This is a time line of Dr. Azikiwe's life: Noting the significant occurrences of his Life.</h3>
          <ul>
            <li><b>1904</b> - Born in Zungeru, Northern Nigeria.</li>
            <li><b>1934</b> - Took editorial position for the "African Morning Post"</li>
            <li><b>1937</b> - Founded the "West African Pilot" to foster Nigerian Journalism. Also became an active member of the "Nigerian Youth Movement"</li>
            <li><b>1944</b> - Co-Foumded the "National Council of Nigeria and the Cameroons" alongside Herbert Macaulay.</li>        
            <li><b>1946-60</b> - Vice President of the Nigerian National democratic Party.</li>     
            <li><b>1960</b> - Queen Elizabeth II appointed him to the "Privy Council of the United Kingdom". </li>    
            <li><b>1960-63</b> - Governor-General and Commander-in-Chief of Nigeria.</li>      
            <li><b>1963-66</b> - President of the Federal Republic of Nigeria</li>            
            <li><b>1980</b> -He was conferred with the highest national honour of Grand Commander of the Federal Republic (GCFR) by the Federal Republic of Nigeria. </li>         
            <li><b>1996</b> - dies at the age of 91.</li>     
            
            
            <p><b>Other Facts:</b> - He won fourteen (14) honorary degrees from Nigerian, American and Liberian universities including Lincoln University, Storer College, </p>
              <p><tr>Howard University, Michigan State University, University of Nigeria, University of Lagos, Ahmadu Bello University, University of Ibadan, Nnamdi Azikiwe University, and University of Liberia.</tr></p> 
          </ul>
          <blockquote>
            <p><i><b>"Originality is the essence of true scholarship. Creativity is the soul of the true scholar. "</i></b></p>
            <footer><cite>Late Dr. Nnamdi Azikiwe</cite></footer>
          </blockquote>
          <h3>Want to know more about Dr. N. Azikiwe? click <a href="https://en.wikipedia.org/wiki/Nnamdi_Azikiwe" target = "blank">Here</a>.</h3>
        </div>
      </div>
    </div> 
  </div>
  <footer class="text-center">
    <hr>
    <p>Developed and Coded by <a href="https://www.freecodecamp.com/shejeebhomee" target="_blank">Oluwasijibomi Ajisegiri</a>.</p>
  </footer>  
</div>  






this is my CSS code

body {
  margin-top: 50px; 
  background: url("http://www.css3.info/wp-content/themes/new_css3/img/betweengrassandsky.png")no-repeat center center fixed;  
  background-size: cover;
}
.thumbnail{
  float: center;
  margin: 25px;
  border-radius: 50%;
 display: block;
  margin-left: auto;
  margin-right: auto;
}
h1, h2, h3, li, p, footer{
  text-align: center;
}

