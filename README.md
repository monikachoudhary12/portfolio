# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio website </title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/c4254e24a8.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    
</head>
<body>
    <div id="header" >
        <div class="container">
            <nav>
                <img src="" class="">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
            <div class="header-text">
                <p>Web Developer</p>
                <h1>Hi, <br>I'm <span>Monika</span><br> Choudhary</h1>
            </div>
        </div>
    </div>
<!-- ------------------------------about------------------------- -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/monu.jpg" >
        
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">
                        About me
                    </h1>
                    <p>
                        Hello, I’m Monika Choudhary, a B.Tech IT student.
                         I have a strong interest web devlopment and  programming, especially in Java . 
                         Currently, I’m focusing on Data Structures and Algorithms .
                          My goal is to become the university topper and excel in placements.
                           I enjoy learning new technologies and working on logical problem-solving.
                    </p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>Web Devlopment</span><br>HTML ,CSS</li>
                            <li><span>Programming Language</span><br>core java and advace java</li>
                            <li><span>Database</span><br>SQL</li>
                           

                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2020</span><br>1st year</li>
                            <li><span>2021</span><br>2nd year</li>
                            <li><span>2022</span><br>3rd  year</li>
                            <li><span>2024</span><br>design page</li>

                        </ul>
                    </div>

                </div>
            </div>
        </div>
    </div>
    <!-- ------------------services----------------- -->
     <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                  
                    <h2>Web Devlopment</h2>
                    
                    <p>
                        Web development is the process of building websites and web applications.
                         It includes frontend development (HTML, CSS, JavaScript) for UI/UX and backend development (Java, Python, Node.js) for server-side logic. Full-stack developers handle both. 
                         Popular tools include React, Django, and databases like MySQL and MongoDB. 🚀
                    </p>
                          <a href="#">Learn more</a>
                </div>
                <div>
                    
                    <h2>Programming Language</h2>
                    
                    <p>
                        Core Java covers the basics of Java programming, including syntax, object-oriented concepts, and essential libraries. Advanced Java builds on that with topics like multithreading, networking, databases (JDBC), and frameworks like Spring, Hibernate for enterprise-level applications and complex projects. 🚀
                    </p>
                          <a href="#">Learn more</a>
                </div>
                <div>
                   
                    <h2>DBMS</h2>
                    <p>
                        A Database Management System (DBMS) is software that stores, organizes, and manages data efficiently. It ensures secure, consistent, and easy data access. Examples include MySQL, PostgreSQL, and MongoDB. 🚀
                    </p>
                          <a href="#">Learn more</a>
                </div>

            </div>
        </div>
     </div>

 <!-- -----------------------contact------------------ -->
 <div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                 <div class="contact-right">
                <form>
                    <label>First Name</label>
                    <input type="text" name="Name"  placeholder="Your Name" required>
                    <br>
                    <br>
                    
                    <label>Email Address</label>
                    <input type="email" name="email" placeholder="Your  Email" required><br>
                    <br>
                    
                    <label>Message</label>
                    <input type="meassge" placeholder="Your msg" name="" id="">
                    <!-- <textarea name="Message"  placeholder="Your Message"></textarea> -->
                    <br>
                    <br>
                    <button class="btn" type="submit">Submit</button>
                   
                </form>
                <br>
                  <p>monikaclg095@gmail.com</p>
                  
                <p>9340480198</p><br>
                <div class="social-icons">
                    <a href="https://facebook.com/"><i class="fab fa-facebook"></i></a>
                    <a href=""><i class="fab fa-linkedin"></i></a>
                    <a href=""><i class="fab fa-instagram"></i></a>
                </div>
            </div>
        </div>
    </div>
  </div>
 
  
   
    </div>
 <script>

        var tablinks=document.getElementsByClassName("tab-links");
        var tabcontents=document.getElementsByClassName("tab-contents");

        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link");
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove("active-tab");
             }
             event.currentTarget.classList.add("active-link");
             document.getElementById(tabnmae).classList.add("active-tab");
        }

</script>
</body>
</html>
