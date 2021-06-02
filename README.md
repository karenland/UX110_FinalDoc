
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 10px;
  background: #F7F1F0
;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  text-align: center;
  background: #FFFFFF;
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
  background-color: #F7F1F0
;
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
  
  /* Center Align Pics
  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
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
    
 
      <p>Not only is reading a popular hobby among the elderly but United States citizens aged 65 years and older are actually the biggest age group that read as a hobby. As more elderly readers are transitioning into e-reading, they need mobile applications where not only can they organize their books but as well as accomplish other book related tasks such as writing reviews, joining book groups, and rating books. All of which help elevate their reading experience. However, there is no good application that keeps in mind the elderly and those who may need more accessibility-friendly design components. This project, named WordsDevoured, provides a new outlet for aging book readers to connect with others as well as delve deeper in their reading journeys by providing users an application with easy transitional steps and the ability to customize their app experience.</p>
       <img src="https://user-images.githubusercontent.com/82078120/120145053-c9839b80-c197-11eb-9a1a-6f659656cf8e.png" alt="HTML5 Icon" width="220" height="220" class="center">
      
    </div>
    
  
    <div class="card">
      <h2>Design Statement</h2>
    
      <p>An important fact to keep in mind about the United States is that the population is aging. By 2080, it is estimated that 25% of Americans from the United States will be over 60 years old.</p>

      <p>Currently, Aging America has actually been struggling with literacy rates. They have limited prose and comprehension skills. While many users are the elderly, many elderly also lose/feel less confident about their reading ability. An app that not only entices avid book readers but also casual readers is very important to combat these issues since a user-friendly app that makes reading fun allows for the elderly not to only engage with others and bring a new level of enjoyment towards a valuable hobby, but it also helps the elderly better their genre literacy and technological literacy skills. So, for my project I hope I can give them an enjoyable app experience that can be paired with their reading journey.
</p>
      
    </div>
    
     <div class="card">
       <h2>Competitor Analysis: Heuristics  </h2>
        
    <p>For this project, we first looked at different competitors and evaluated them using Nielson’s 10 Heuristic evaluation. Again, my goal is to create a social media app for book readers. So I looked at GoodReads and Libby. Both of these applications have different goals and purposes. GoodReads, while a book-related application app for readers, is an archive and social media app. Its goal is “to help people find and share books they love.” While Libby is an e-reading application. And by working with thousands of libraries and schools, they hope their application can lead to “ a world enlightened by reading.” They both have similar features such as readers can create book lists and have customizable search features. However, they do share some heuristic violations that causes the app experience for both to feel limiting and a bit confusing . So during this heuristic process I analyzed some of the apps’ features that could be improved and implemented. </p>
<ul>
  <li> <b>Recognition rather than recall/User Control and Freedom:</b> Again, for both applications, there is a customizable search feature but it is limiting. Typos stump the search feature. You also cannot search by genre, character, or publication year. So if a user cannot remember the title of the title, they cannot find the book. A more flexible search feature would be suitable for these apps but especially for GoodReads since this app has a lot of searchable items such as book lists, authors, and book groups.</li>
  <li><b>Aesthetic and minimalist design:</b> Libby’s app is very consistent and it makes it obvious that the app is an ereader. For example, for the previous searches, they are all italicized because in writing, book titles are usually italicized. While for BookReads there are a lot of inconsistencies in the design, there are blue links when the app itself is based on a warm-brown color palette. Also the buttons are different colors: some are green while others are a dark turquoise</li>
</ul>
<p>
  More information about these evaluations can be found <a href="https://github.com/karenland/DH110-AssignOne">here!</a> 
   </p>     
</p>
    </div>
    
      <div class="card">
     <h2>Competitor Analysis - Usability Testing:</h2>
   
      <p>
       Again, GoodReads is a popular app for avid book readers. It allows users to friend one another, write reviews, create book lists and even join book groups to discuss reads with fellow peers. 
So for this project, the Usability Test will ask the user to perform some tasks on the GoodReads IOS application. From their interactions and comments, we are able to learn more about the site’s interface as well as to study its strengths/weaknesses. Generally, UT is an important step during the UI process because it enables the designers and researchers to efficiently study user behavior and opinions to create a better project early in stages of the project. The two tasks the user were asked to do was to: 
 <ol>
  <li>search for your favorite book, give it a start-rating, and then write a review about it.</li>
  <li>Explore a book’s info/profile page</li>
  <li>Create a bookshelf with at least three books</li>
  <li>Revisit the user’s review to see if it has any comments </li>
  <li>Reply to any comments then log out</li>      
</ol>
        </p>
  <iframe src="https://drive.google.com/file/d/1fsU-k4uL2_A8_3fi7ztxDTjwCGkFrux2/preview" width="640" height="480"></iframe>  
      <p>  
       More info can be found about my Usability Testing procedures and results can be found <a href="https://github.com/karenland/DH-110_AssignTwo">here!</a> 
        </p>
    </div>
    
    
      <div class="card">
       <h2>UX Research: Contextual inquiry </h2>
        
      <p>To further study the user, specifically the context experience exists in, we used Contextual Inquiry. This qualitative data collection method allows us to observe people and ask for feedback as they are doing tasks. So for the book-reading experience, we get to learn about not simply the basic tasks one might do outside of applications but also their thoughts and emotions that go along with the reading journey. The results of this method allow us to better define the requirements and improvements that the book domain needs. For this project, the participant was asked how they generally search and look up books as well as how would they describe their reading experiences (eg. a solitary excursion or one shared with friends/peers).</p>
 
    <iframe src="https://drive.google.com/file/d/1A9Op-9gt_BX2Blk7CnnSQ0gAEM4ylzyR/preview" width="640" height="480"></iframe>
   <p>     
More info can be found <a href="https://github.com/karenland/DH110-Assign3">here!</a> 
</p>
    </div>
    
     <div class="card">
       <h2>UX StoryTelling: </h2>
        
      <img src="https://cdn1.parksmedia.wdprapps.disney.com/resize/mwImage/2/1280/720/75/dam/disneyland/home/destination/sleeping-beauty-castle-tint-16x9.jpg" alt="HTML5 Icon" width="210" height="210">
      <p>UX storytelling is when researchers create and utilize personas, journey maps and other storytelling components in order to build empathy and as well get insight into users. Storytelling is also useful as a means to present ideas and gain new ones as you explore the word through the user’s eyes. To add, this process allows the whole team working on the project to be aware of the users’ needs. My design is basically a revamped GoodReads app formatted for the elderly. The personas I created are of two elderly users both with deep love and appreciation books but their goals are different. One reads to learn new things and the other reads to bond with her family as well as emerge herself into fictitious worlds.</p>

       <p>Key features of design:</p>
<p>Generally speaking, the apps I explored related to my project are all extremely limiting so the functions I have focusing on will simply give users more freedom.
 <ol>
  <li>An updated search function that filters results by if the search inquiry is a book, another user, author, a book list, or a book group</li>
  <li>The ability to change the language of the app</li>   
</ol>
</p>
  
  <p> Below is the first User Persona William:</p>
    <img src="https://user-images.githubusercontent.com/82078120/116471280-56e66f80-a829-11eb-8e64-7331db7967bc.png" alt="Persona1">
   <img src=" https://user-images.githubusercontent.com/82078120/116472545-dfb1db00-a82a-11eb-8eea-fa4373b7e40a.jpg" alt="Persona1Steps">
    </p>
More info about my personas <a href="https://github.com/karenland/DH110_Assignment4">here!</a> 
</p>
    </div>
    
      <div class="card">
       <h2>Low-Fidelity prototype</h2>
        
         <p>The purpose of creating low fidelity prototyping is to test the project’s flow and interactions; making shows that both are intuitive for the user. There is a lot of benefits in creating and testing low-fidelity prototypes such as it puts no pressure on the users since it is an “early” version of the product, less time to create, and ideas/screens can easily be changed/modified. To add,  testing my Low-Fidelity Prototypes allowed me to see early on in the design process what is intuitive for the user as they see my screens; thus, I was able to come up with new designs and prep them for my high-fidelity prototypes. For example, since it is a social-media based app for the elderly, my initial screens and features had the images/profile icons make up most of the screen to make sure that they are easily visible. </p>
           
          <p> The screens show :</p>
          <ol>
          <li> Task One: search for a book group. (image 1) </li>
          <li> Task Two: Favorite a book. (image 2) </li>
           
  </ol>  
      <img src="https://user-images.githubusercontent.com/82078120/117216097-1b611d80-adb4-11eb-8310-0d20167996a9.jpg" alt="wireframes1" width="360" height="360" class="center">
         <img src="https://user-images.githubusercontent.com/82078120/117216106-1c924a80-adb4-11eb-8266-9cad1b171f04.jpg" alt="wireframes 2" width="360" height="360" class="center">
     

<p>
More info about my this round of prototyping can be found <a href="https://github.com/karenland/DH110_Assign5">here!</a> 
</p>
    </div>
  
  
  
  <div class="card">
    <h2>High-Fidelity prototype</h2>
      <p>
High-Fidelity prototyping is when you start creating the project as similar as possible to the actual product. With the information from the past tests, this round of prototypes incorporates all that the team has learned so far. Some benefits to this version of prototyping is that it serves as a good deminstrations for the client, it allows the team to test specific components of the design, and useful information can be distilled from user testing. To bring up another interesting part of this process, my High-Fidelity prototype differed greatly from my low-fidelity prototype; it was interesting to see just from how just one round of testing can greatly affect the design of the product. 
</p>

    <iframe style="border: 1px solid rgba(0, 0, 0, 0.1)" width="640" height="480" src="https://framer.com/embed/assignment8--dYCfCRPpRIGkUAlJaR7r/CXGluMJjp" allowfullscreen></iframe>
    
<p>
More info can be found <a href="https://github.com/karenland/DH110_Assign6">here!</a> 
</p>
    </div>
 
    
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me!</h2>
      <div class="fakeimg" style="height:100px;">Image</div>
      <p>Hello! Hello! My name is Karen L. I am an Applied Linguistics major and double minoring in Cognitive Science and Asian Languages. I find the the relationship of culture and language so fasincating! And a great example of this relationship are the books we read!! </p>
    </div>
    


