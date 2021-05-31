
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 10px;
  background: #f1f1f1;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  text-align: center;
  background: white;
}

.header h1 {
  font-size: 50px;
}


/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
  
  
  img {
  width: 160%;
}
}
</style>
</head>
<body>

<div class="header">
  <h1>WordsDevoured</h1>
  <p>Let's Talk Books!</p>
</div>



<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>Introduction</h2>
      <h5>basics and more </h5>
    
      <p>Some text..</p>
      <p>Not only is reading a popular hobby among the elderly but United States citizens aged 65 years and older are actually the biggest age group that read as a hobby. As more elderly readers are transitioning into e-reading, they need mobile applications where not only can they organize their books but as well as accomplish other book related tasks such as writing reviews, joining book groups, and rating books. All of which help elevate their reading experience. However, there is no good application that keeps in mind the elderly and those who may need more accessibility-friendly design components. This project, named WordsDevoured, provides a new outlet for aging book readers to connect with others as well as delve deeper in their reading journeys by providing users an application with easy transitional steps and the ability to customize their app experience.</p>
    </div>
    
  
    <div class="card">
      <h2>Design Statement</h2>
    
      <p>An important fact to keep in mind about the United States is that the population is aging. By 2080, it is estimated that 25% of Americans from the United States will be over 60 years old.</p>

      <p>Currently. Aging America has actually been struggling with literacy rates. They have limited prose and comprehension skills. While many users are the elderly, many elderly also lose/feel less confident about their reading ability. An app that not only entices avid book readers but also casual readers is very important to combat these issues since a user-friendly app that makes reading fun allows for the elderly not to only engage with others and bring a new level of enjoyment towards a valuable hobby, but it also helps the elderly better their genre literacy and technological literacy skills. So, for my project I hope I can give them an enjoyable app experience that can be paired with their reading journey.
</p>
    </div>
    
      <div class="card">
      <p>Some text..</p>
      <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    </div>
    
    
    
      <div class="card">
      <p>Some text..</p>
      
      <img src="https://cdn1.parksmedia.wdprapps.disney.com/resize/mwImage/2/1280/720/75/dam/disneyland/home/destination/sleeping-beauty-castle-tint-16x9.jpg" alt="HTML5 Icon" width="210" height="210">
      <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    </div>
    
    
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <div class="fakeimg" style="height:100px;">Image</div>
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    </div>
    


