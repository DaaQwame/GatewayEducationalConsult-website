<template>
<header class="head">
  <div class="sod">
    <div class="gee">
    <img class="play"  src="../assets/homeb.jpg">
    </div>
    <div class="gee">
    <img class="play" src="../assets/gec13.jpeg">
    </div>
    <div class="gee">
      <img class="play" src="../assets/tt.jpg">
    </div>
  </div>
</header>
<section class="content">
  <h3>WHAT WE DO</h3>
  <p class="blay">Gateway educational consult popularly known as gec has contribute alot to students who wants to study abroad.</p>
  <div class="row">
    <div class="content-col">
      <h3>Our Mission</h3>
      <p class="text">Gateway educational consult arrive to the need of students who want to study across
       the globe to achieve their dream of studying in their dream country to come true.Gec
       has helped over thousands of students to study worldwide,and this is a great
       opportunity for you to get in touch with us to study in your dream country,and
       to also testify about the good work of gateway educational consult.
       </p>
    </div>
    <div class="content-col">
      <h3>Our Focus</h3>
      <p class="text">Gec management have taken it upon themselves to push every soul who is far and near.
        And has the zeal to proceed his or her academic journey in different country to pass
        it through successfully without much demand from them.Our target every year is to send
        more then thousand students to continue their academic journey in their country of choice,
        apply through us now.
      </p>
    </div>
  </div>

</section>

<!-------------countries---------->

<section class="countries">
  <h2 class="like">COUNTRIES YOU CAN STUDY</h2>
  <p>students can apply from any country of their choice to study</p>


  <div class="raw">
    <div class="facilities">
      <img src="../assets/germany1.webp">
      <h3>GERMANY</h3>
      <p>There are many great advantages for studying in Germany.
        Excellent universities offer a wide range of courses, many
        taught in English. Most courses have no tuition fees, and
        students should find the cost of living affordable. There is
        a lot of support available for international students, who
        will feel welcomed into this fascinating, cosmopolitan country.
      </p>
    </div>
    <div class="facilities">
      <img src="../assets/uk.jpg">
      <h3>UNITED KINGDOM</h3>
      <p>The UK has become one of the top destinations to study around the
         world. From world-
         recognised universities to innovative teaching approaches with leading
          minds to deliver it.The UK has respectfully earned itself recognition
          as one of the leading destinations to help shape ambitious young minds
           and help you achieve your potential.
      </p>
    </div>
    <div class="facilities">
      <img src="../assets/china.jpeg">
      <h3>CHINA</h3>
      <p>Studying in China is an excellent opportunity to explore the world's most
         populous country. You will experience China's unique blend
         of ancient and modern civilization, as well as its scenic beauty and
         bustling nightlife. Visit new places with other students from around
         the world who you meet,apply through gec now to help build your future
         together.
      </p>
    </div>
  </div>


  </section>

  <!-------------countries---------->

  <section class="countries">
    <div class="raw">
    <div class="facilities">
      <img src="../assets/russia.jpg">
      <h3>RUSSIA</h3>
      <p>Russia possesses one of the best mass-education systems in the world,
         and has a long-standing
         tradition of high-quality education for all citizens. Russia's education
          system produces a 98% literacy
          rate, exceeding that of most Western European countries. Russia's top
          universities are located in
          Moscow and St. Petersburg, with Moscow State University and Saint
          Petersburg being the most well
          known.
      </p>
    </div>
    <div class="facilities">
      <img src="../assets/australia.jpg">
      <h3>AUSTRALIA</h3>
      Australian universities are strong in research, excelling in area such as
       arts and humanities, education
       and sciences. Australia is also a proud contributor to global research,
       credited for many important
       students — whether you want to learn from the best in a coursework degree
        or undertake your own research.
      <p>
      </p>
    </div>
    <div class="facilities">
      <img src="../assets/usa.jpg">
      <h3>UNITED STATES OF AMERICA</h3>
      <p>Studying abroad in America provides an ideal environment for students,
        characterized by flexible
        methods of education and continuous development process for students in
         the various fields of studies.
         Depending on your strengths, interests, and goals, U.S. universities
         declassroom structures and instruction methods to make learning engaging
         and, at the same time, relevant to your own domain.liberately shift their
      </p>
    </div>
  </div>
</section>
  <!----------our help for student------>

  <section class="mama">
    <h1>OUR HELP FOR STUDENTS</h1>
    <video class="ac" controls="controls" poster="../assets/gat.jpg">
      <source src="../assets/gec14.mp4">
    </video>
   </section>

  <!---------------footer------>

  <footer>
     <div class="container">
       <ul class="flex">
         <li><router-link class="you" to="/">Home</router-link></li>
         <li><router-link class="you" to="/About">About</router-link></li>
         <li><router-link class="you" to="/Service">Service</router-link></li>
         <li><router-link class="you" to="/Testimonial">Testimonial</router-link></li>
         <li><router-link class="you" to="/Contact">Contact</router-link></li>
       </ul>
       <ul class="flex">
         <a class="you" to="/www.facebook.com"><li><i class="fab fa-facebook"></i></li></a>
        <router-link class="you" to="/twitter.com"><li><i class="fab fa-twitter"></i></li></router-link>
        <router-link class="you" to="/"><li><i class="fab fa-instagram"></i></li></router-link>
       <router-link class="you" to="/"><li><i class="fab fa-youtube"></i></li></router-link>
       </ul>
         <p class="run"><i class="fa-regular fa-copyright"></i> 2022 Gateway Educational Consult</p>
     </div>
     </footer>
</template>
<script>

</script>
<style>
.head{
  height: auto;
  overflow: hidden;
}
.head .sod div{
  float: left;
  width: 20%;
}
.gee{
  height: 70vh;
}
.head .sod .play{
width: 100%;
height: auto;
float: left;
}
.head .sod{
  position: relative;
  width:500%;
  margin: 0px;
  left: 0;
  animation: 40s ravi infinite;
}
@keyframes ravi{
  0%{
    left: 0%;
  }
  5%{
    left: -100%;
  }
  10%{
    left: -100%;
  }
  17%{
    left: -100%;
  }
  20%{
    left: -100%;
  }
  24%{
    left: -100%;
  }
 27%{
  left: -100%;
 }
 30%{
  left: -100%;
 }
 33%{
  left: -200%;
 }
 36%{
  left: -200%;
 }
 40%{
  left: -200%;
 }
 43%{
  left: -200%;
 }
 46%{
  left: -200%;
 }
49%{
  left: -200%;
}
55%{
  left: -100%;
}
58%{
  left: -100%;
}
63%{
  left: -100%;
}
66%{
  left: -100%;
}
69%{
  left: -100%;
}
76%{
  left: -100%;
}
80%{
  left: 0%;
}
82%{
  left: 0%;
}
83%{
  left: 0%;
}
}
.mama{
  padding-top: 60px;
}
.mama, h1{
  color: #111;
  margin-bottom: 2%;
}

.ac{
  width: 60%;
  border-radius: 5px;
  border: 3px solid brown;
}
ul{
  margin-bottom: 50px;
  flex-wrap: wrap;
  justify-content: center;
}

li{
  padding: 0 20px;
  margin-bottom: 16px;
  list-style: none;
}
.run{
  color: #fff;
  font-size: 15px;
}
footer{
  color: rgb(241, 229, 229);
  background-color: brown;
}
.flex{
  display: flex;
  flex-direction: row;
  align-items: center;
}

.you{
  color: #fff;
  font-size: 14px;
  font-weight: 500;
  text-decoration: none;
}
.countries{
  width: 80%;
  padding-top: 80px;
  text-align: center;
  margin: auto;
}
.facilities img{
  width: 100%;
  border-radius: 10px;
}
.facilities p{
  padding: 0;
}
.facilities h3{
  margin-top: 16px;
  margin-bottom: 15px;
  text-align: left;
}
.facilities{
  flex-basis: 31%;
  border-radius: 10px;
  margin-bottom: 5%;
  text-align: left;
}
.raw{
  margin-top: 5%;
  display: flex;
  justify-content: space-between;
}
.like{
  font-size: 23px;
  font-weight: 300;
}
.text{
  color: rgb(249, 245, 245);
}
.row{
  margin-top: 5%;
  display: flex;
  justify-content: space-between;
}
.content-col{
  flex-basis: 45%;
  background-color: #777;
  border-radius: 10px;
  margin-bottom: 5%;
  padding: 20px 12px;
  box-sizing: border-box;
}
.content{
  width: 80%;
  padding-top: 100px;
  text-align: center;
  margin: auto;
}
p{
  color: #777;
  font-size: 14px;
  font-weight: 300;
  line-height: 22px;
  padding: 10px;
}
@media only screen and (max-width: 700px) {
  .row{
    flex-direction: column;
  }
  .ac{
    width: 80%;
  }
  .head{
    height: 40vh;
  }
  .mama, video{
    width: 100%;
  }
  .raw{
    flex-direction: column;
  }
   .run{
    margin-top: -8%;
  }
   .flex{
    padding-right: 8%;
  }
}
</style>