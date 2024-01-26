# My-First-Project
A basic website of our college using HTML & CSS

 <!DOCTYPE html>                      
<html lang="en">
<head>
    <title>GG WEBPAGE</title>
 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
 
    <style>
        *{
            margin: 0;
            padding: 10px;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }
        
        h1{
           text-align: center;
           color: black;
           background-color:red ;
           margin-top: 5px;
           margin-left: 400px;
           margin-right: 400px;
           border: 1px solid black;
        }
        
        h2{
            background-color: white;
            color: black;
            text-align: center;
            margin-left: 550px;
            margin-right: 550px;
            border-radius: 7px;
        }
        
        .navbar{
            display: flex;
            justify-content: space-between;
            align-items: center;
            background:linear-gradient(rgb(198, 178, 153),rgb(67, 185, 218));
            border-radius: 5px;
            border: 2px black solid;
        }
        
        .links ul{
            display: flex;
        }
        
        .links ul li{
            list-style-type: none;
            text-decoration: none;
            margin-left: 50px;
        }
        
        .navbar .links ul li a{
            color: black;
            text-decoration: none;
        }
    
        #home{
            height: 80vh;
            background-image: url(https://img.freepik.com/free-photo/top-view-statistics-presentation-with-arrow_23-2149023752.jpg?size=626&ext=jpg&uid=R121447584&ga=GA1.1.1826595276.1697538276&semt=ais);
             background-repeat:no-repeat;
            background-size:cover;  
        }
        
        #about{
            height: 120vh;
            background-image: url(https://img.freepik.com/free-photo/abstract-blue-geometric-shapes-background_24972-1841.jpg?size=626&ext=jpg&uid=R121447584&ga=GA1.1.1826595276.1697538276&semt=ais);
            background-repeat:no-repeat;
            background-size:cover;
            display: flex;
            flex-direction: column;
            justify-content:center;
            align-items:center;
            text-align:center;
        }
        #contact{
            height: 100vh;
            background-image: url(https://img.freepik.com/free-photo/vintage-pink-telephone-composition_23-2148913955.jpg?size=626&ext=jpg&uid=R121447584&ga=GA1.1.1826595276.1697538276&semt=ais);
            background-repeat:no-repeat;
            background-size:cover;
            display: flex;
            flex-direction: column;
            justify-content:center;
            align-items:center;
            text-align:center;
        }
        #courses{
            height: 80vh;
            background:linear-gradient(rgb(214, 75, 75),rgb(194, 194, 96));
        }
        #achievements{
            height: 100vh;
            background:linear-gradient(rgb(118, 118, 215),rgb(79, 188, 152));
        }
        p{
            text-align: center;
        }
        #img1{
            margin-left: 450px;
            border: 4px solid black;
        }
        h3{
            text-align: center;
        }
        #img2{
            margin-left: 590px;
            margin-top: 20px;
            border: 4px solid black;
            border-radius: 5px;
        }
         #img3{
            margin-left: 480px;
        }
        .section3 .icons{
            background-color: white;
            width: 90px;
            height: 250px;
            position:fixed;
            top: 600px;
            left: 1710px;
            border: 2px solid black;
            border-radius: 5px; 
        }   
        .section3 .icons i{
            display: flex;
            flex-direction: column; 
            font-size: 50px;
            width: fit-content;
            padding: 11px;
        }
        .fa-facebook{
            color: blue;
        }
        .fa-instagram{
            color:palevioletred;
        }
        .fa-twitter{
            color: skyblue;
        }
        .btns{
            border: 1px solid black;
            background-color: white;
            border-radius: 5px;
        
        }
        .btns1{
            border: 1px solid black;
            background-color: white;
            border-radius: 5px;    
        }
        
    </style>
    </head>
    <body>
            <h1>GIRRAJ DEGREE COLLEGE(A)</h1>
            <br><br><br>
        <div class="navbar">
        <div class="logo">
            <img src="../IMAGES/PHOTOS/GG LOGO.jpg" alt="" height="200px">
        </div>
        <div class="links">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#courses">Courses</a></li>
                <li><a href="#achievements"> Achievements</a></li>
            </ul>
        </div>
        <div class="btns">
            <a href="login.html">LogIn</a>
        </div>  
        <div class="btns1">
            <a href="register.html">Register</a>
        </div>
        </div>
              <br><br>
        <div id="home">
            <h2><u>Home</u> </h2>
            <p><u>GIRRAJ DEGREE COLLEGE(Autonomous)</u></p>
            <p>(Reaccredited with 'B' Grade By NAAC)</p> 
            <p> Affiliated to Telangana University</p>  
            <P> Dubba Road,Nizamabad,503002.</P>
            <img id="img1"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSTHxUizEodhOxZh7pxFwambW7XQ9r6ncpxnah07-BroSIqa3jbIP90X7oGVaDPVEsM_NY&usqp=CAU" alt="" width="500px">
        </div>
                 <br>
        <div id="about">
            <h2><u>About</u></h2>
            <p><u>About College-Brief History of the College:</u></p>
                   <br>
            <p>Girraj Govt.College (A), Nizamabad was established in the year 1956 in the premises of Quilla under private management. It was affiliated to Osmania University from the time of establishment and continued its affiliations under O.U till 2008. Now the College is affiliated to Telangana University, Dichpally, Nizamabad.
   
                The college was named after Sri.Girrajmalji Agarwal who has generously donated Rs.50,001/-for the establishment of this college. The college was taken over by the Government of A.P in 1960. It was shifted to this campus in 1968. The college campus has an area of 27.3 Acres.
       
                Since its establishment, the College was imparting the education at UG Level and becoming an educational umbrella for the students of Adilabad, Nizamabad, some parts of Medak and neighboring states of Maharastra and Karnartaka. It had been catering to be Higher Educational needs of all sections of the society.
       
                The College has shown enormous and vast improvement with regard to the courses offered and in the strength of the students seeking admission. At present the College is imparting education to 2419 in 20 U.G Courses and 522 students in 9 PG Courses. However, the infrastructural facilities are not sufficient to accommodate to all the facilities to the students.
       
                The College result pass percentage is much higher than the University average. And career opportunities to pursue their Higher Education after UG Courses is increasingly progressive from one batch to next batch.
       
               Girraj Govt. College excels in the quality of education with a scope for further improvement to attain deemed University status. The College has the following immediate requirement in the infra- structure so that it can have an immediate access with the modern technological and scientific advancement and can also make the students Globally competent. The College was given autonomous status in the Academic Year 2004-2005 which was extended further up to 2010 to 2015 by UGC. Recently autonomy team has extended the autonomous status from 2016 to 2022 because of quality maintained by the Institution in teaching evaluation process. The College is District Resource Centre and monitor the academic quality of all the Govt. Degree colleges in the District through sharing of knowledge and resource persons. The College continuously take measures to maintain internal quality by conducting National Seminars / Workshops / Symposia / Field trips / Industrial tours and many such knowledge exchange programmes there by making the faculty and the students updated in the arena of knowledge & I.T and makes the stake holders globally competent. The College was re accredited by NAAC with Grade “B” in 2012.
            </p>
            <br><br>
            <p><u>Vision: </u> </p> 
                   <br>
            <p>To build a vibrant multicultural learning environment founded on value based academic principles, wherein all involved shall contribute effectively, efficiently and responsibly to the Nation and Global Community.
            </p>          
            <br><br>
            <p><u>Mission:</u></p> 
            <br>
            
            <p>☀ To enhance access and inclusivity in quality education.</p>           
            <p>☀ To provide a context of learning that enhances professionalism, humanism and social responsibility.</p>  
            <p>☀ To empower students to assume leadership.</p> 
            <p>☀ To develop critical thinkers and concerned citizens.</p> 
            <p>☀ To generate skill based education to get employability.</p>
            <p>☀ To make aware the students to feel social responsibility and become a good citizen of the Nation.</p>
            
            <img src="" alt="">
        </div>
              <br>
        <div id="contact">
            <h2><u>Contact</u></h2>
            <p><u>Contact us</u></p>
            <p> Girraj Government College(Autonomouns)</p>
            <p>Nizamabad, Telangana-503002</p>
            <p>Phone: +91 9440019918</p>
            <p>Email: prl-gdc-nzb-ce@telangana.gov.in</p> 
            <p>Location: https://goo.gl/maps/EhVX1o3zEuo3vyD18</p>
            <img src="https://img.freepik.com/premium-photo/business-website-page-contact-businessman-touching-contact-us-icons-customer-service-include-telephone-address-email-message-by-3d-render_50039-2828.jpg?size=626&ext=jpg&uid=R121447584&ga=GA1.1.1826595276.1697538276&semt=ais" alt="" height="300px">
        </div>
                   <br>
        <div id="courses">
            <h2><u>Courses</u></h2>
            <h3><u>UG Courses (For the Academic Year -2022-23)</u></h3>
            <p>B.Sc. COURSE (Physical Sciences)</p>
            <p>B.Sc. COURSE (Life Sciences)</p>
            <p>B.Com. COURSE</p>
            <p>BA COURSE</p>
            <img id="img3" src="https://img.freepik.com/premium-photo/rear-view-audience-listening-asian-speaker-stage-meeting-room_41418-4150.jpg?size=626&ext=jpg&uid=R121447584&ga=GA1.1.1826595276.1697538276&semt=sph" alt=""  height="300px">
        </div>
                    <br>
        <div id="achievements">
            <h2><u>Awards & Achievements</u></h2>
            <p>Government College, Nizamabad a prestigious Institute of Higher Education in
            the Entire Telangana State was established in 1956. It was named after a philanthropist
            Sri.Girrajmalji Agarwal. The college attracts students not only from the districts but also
            students from neighbouring districts and states. It was affiliated to Osmania University,
            Hyderabad and presently it is affiliated to Telangana University, Nizamabad. It is one of the
            premier Institutes to be accorded Autonomous status by UGC in 2005. It was conferred with
            CPE ( College with Potential for Excellence) in 2010. It has completed three cycles of NAAC
            accreditations and presently it is reaccredited with “B”. Now it stands at 37th position among
            all the Government Autonomous Colleges in the Country declared by EWNIRF ranking –
            2020. It was the centre for community development under UGC in the year 2016 – 2017 and
            successfully completed two courses in Retail Management and computerized accounting. The
            College has bright glory of Alumina occupying top positions in services and other fields. The
            college offers 40 U.G Courses & 09 P.G Courses with strength of more than 4000 students.
            For the last three consecutive years our college has topped in DOST admissions in the entire
            Telangana State. The College has a team of qualified, committed and dedicated staff, who
            thrive a lot for the betterment of the students in all sectors. The qualitative & quantitative
            results of the college substantiate its strength, keeping in view the changing global scenario;
            the faculty has introduced lot of programmes, Seminars, Workshops, Extension Lectures,
            conduction of National Seminars etc. for the benefit of students thereby empowering them to
            take the challenges ahead. The college has secured the Academic Excellence Award for
            successive four consecutive years from 2015, 2016, 2017 & 2018. Recently we were awarded
            the ISO (9001:2015) Certification by our Honourable Commissioner Sri.Navin Mittal, IAS.</p>
            <img id="img2" src="../IMAGES/PHOTOS/GGCERTIFICATE.jpeg" height="350px">
        </div>    
    <div class="section3">
        <div class="icons">
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-twitter"></i>
        </div>
    </div>       
</body>
</html>  
