---
permalink: /
title: ''
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-149714426-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
</script>

<div class="navbar">
  <a href="#about">About</a>
  <a href="#experience">Experience</a>
  <a href="#projects">Projects</a>
  <a href="#publications">Publications</a>
  <a href="#education">Education</a>
  <a href="#contact">Contact</a>
</div>

<h2 class="section-header">About me</h2>
<div id="about" class="about-item">
I am pursuing my PhD at the University of Warwick, UK,  under the supervision of Dr. Mehrdad Dianati, Dr. Kurt Debattista and Dr. Valentina Donzella. My research focuses on adapting deep generative models to synthesise realistic camera images and Lidar point clouds for autonomous driving applications.<br>
 Simultaneously, I work as a part-time machine learning engineer in the European Union-funded project, Hi-Drive. Here, I am involved in developing ML-ADA, a semi-automated annotation tool for 2D/3D object detection.  <br>
 Overall, I specialise in leveraging state-of-the-art ML models, particularly deep generative models, and computer vision algorithms to solve real-world problems.<br>
 <a href='../assets/Hamed_CV.pdf' style="color: #007bff">View my CV for more details.</a>
</div>

<h2 class="section-header">Experience</h2>
<div id="experience" class="experience">
  <div class="experience-item">
    <h3>ML Engineer (part-time)</h3>
    <p><strong>Hi-Drive</strong>, March 2022 - Feb 2024, Coventry, UK</p>
    <ul>
      <li>&bull; Developed a semi-automatic data annotation tool (ML-ADA) for 2D/3D object detection tasks. ML-ADA resulted in reducing the manual labelling effort in autonomous driving.</li>
      <li>&bull; Designed experiments to approximate the manual annotation effort needed at various levels of automation.</li>
      <li><a class="code" href="https://github.com/hamedhaghighi/ML-assisted-annotation" >code</a></li>
    </ul>
  </div>

  <div class="experience-item">
    <h3>Teaching Assistant</h3>
    <p><strong>University of Warwick</strong>, 2021 - 2024, Coventry, UK
     <ul>
    <li>Machine Intelligence and Data Science (MIDS)</li>
    <li>Dr. Mehrdad Dianati</li>
    </ul>
    </p>
    <ul>
      <li>&bull; Assisted in designing and delivering tutorials for the module, with a focus on implementing fundamental deep learning models using the PyTorch library.</li>
      <li>&bull; Assisted in designing post-module assessments and marking students.</li>
    </ul>
    <p><strong>University of Tehran</strong>,  2017 - 2019, Tehran, Iran
    <ul>
    <li>Pattern Recognition, Computer Vision, Data Analytics</li>
    <li>Dr. Babak Nadjar Aarabi, Dr. Reshad Hosseini, Dr. Mohammad Amin Sadeghi</li>
    </ul>
     </p>
    <ul>
      <li>&bull; Assisted in designing and marking course final projects, as well as grading final exams.</li>
    </ul>
  </div>

  <div class="experience-item">
    <h3>Freelance</h3>
    <p><strong>Collaboration with Dr. Peyman Gifani @ University of Cambridge</strong>, Feb 2020 - May 2020, Remote</p>
    <ul>
      <li>&bull; Successfully reproduced the results of the outstanding <a href="https://www.nature.com/articles/s41467-019-13807-w" target="_blank">paper</a> on generating hit-like molecules from gene-expression using deep generative models.</li>
      <li>&bull; Adapted techniques from <a href="https://arxiv.org/pdf/2002.12826.pdf" target="_blank">Podda <em>et al.</em></a> and <a href="https://pubs.acs.org/doi/epdf/10.1021/acs.jcim.9b00237" target="_blank">Yang <em>et al.</em></a>  to use fragment graphs, a more expressive molecule representation, instead of SMILES. This change resulted in generating more unique and valid molecules.</li>
    </ul>
  </div>

  <div class="experience-item">
    <h3>Summer Intern</h3>
    <p><strong>Medical Image and Signal Processing Research Centre</strong>, Summer 2016, Isfahan, Iran</p>
    <ul>
      <li>&bull; Developed innovative software using image processing techniques to automate the evaluation of crown preparation. This tool is designed to assist students in comparing their crown work against standard parameters during preclinical tooth preparation.</li>
      <li>&bull; Assisted in writing a paper on the evaluation of the software's effectiveness by comparing it with the expert crown preparation. <a href="https://journals.lww.com/jmss/fulltext/2020/10040/Automatic_Evaluation_of_Crown_Preparation_Using.3.aspx" target="_blank">paper link</a></li>
    </ul>
  </div>
</div>

<h2 class="section-header">Projects</h2>

<div id="projects" class="project-grid">

  <div class="project-item" data-link="https://github.com/hamedhaghighi/ML-assisted-annotation">
    <img src="../images/MLADA.jpg" alt="ML-ADA">
    <div class="project-info">
      <h3>ML-ADA</h3>
      <p>Developed a semi-automatic data annotation tool (ML-ADA) for 2D/3D object detection tasks in autonomous driving.</p>
    </div>
  </div>

 <div class="project-item" data-link="https://arxiv.org/pdf/2404.05505.pdf">
    <img src="../images/LidarGRIT.png" alt="LidarGRIT">
    <div class="project-info">
      <h3>LidarGRIT</h3>
      <p>Developed a transformer-based model, LidarGRIT, for synthesising realistic Lidar point clouds.</p>
    </div>
  </div>


 <div class="project-item" data-link="https://github.com/hamedhaghighi/ETSSR">
    <img src="../images/ETSSR.png" alt="ML-ADA">
    <div class="project-info">
      <h3>ETSSR</h3>
      <p>Developed a stereo super resolution model, ETSSR, tailored for accelerating stereo image rendering.</p>
    </div>
  </div>

  <div class="project-item" data-link="https://github.com/hamedhaghighi/CLS2R">
    <img src="../images/cls2r.png" alt="ML-ADA">
    <div class="project-info">
      <h3>CLS2R</h3>
      <p>Developed a sim-to-real mapping framework for Lidar point clouds.</p>
    </div>
  </div>






  <div class="project-item" data-link="https://github.com/hamedhaghighi/Ambient-VAE">
    <img src="../images/ambient-VAE.png" alt="ML-ADA">
    <div class="project-info">
    <h3>Ambient-VAE</h3>
      <p>Adapted varational auto-encoders for unsupervised image restoration</p>
    </div>
  </div>
  
  <div class="project-item" data-link="https://github.com/hamedhaghighi/UTLC">
    <img src="../images/UTLC.png" alt="ML-ADA">
    <div class="project-info">
    <h3>UTLC</h3>
      <p>Designed a fast recursive model, UTLC, for lossless image compression using attention mechanism.</p>
    </div>
  </div>

  <div class="project-item" data-link="https://github.com/hamedhaghighi/SampleTransformer">
    <img src="../images/sampleTransformer.jpg" alt="ML-ADA">
    <div class="project-info">
    <h3>SampleTransformer</h3>
      <p>Designed a music generative model, SampleTransformer, using an U-Net-based transformer architecture.</p>
    </div>
  </div>

  <div class="project-item">
    <img src="../images/e-puck.png" alt="ML-ADA" data-link="/">
    <div class="project-info">
    <h3>E-puck Robot Localisation</h3>
      <p>Implemented the particle filter algorithm for real-world problem of E-puck robot localisation.</p>
    </div>
  </div>

  <div class="project-item" data-link="https://journals.lww.com/jmss/Fulltext/2020/10040/Automatic_Evaluation_of_Crown_Preparation_Using.3.aspx">
    <img src="../images/AECP.jpeg" alt="ML-ADA">
    <div class="project-info">
    <h3>Automatic Evaluation of Crown Preparation</h3>
      <p>Designed and implemented an innovative software for evaluating crown(tooth) preparation.</p>
    </div>
  </div>
</div>

<h2 class="section-header">Publications</h2>
<div id="publications" class="publications">
  <div class="publication-item">
    <h3>Taming Transformers for Realistic Lidar Point Cloud Generation</h3>
    <p><em>H. Haghighi, A.Samadi, M. Dianati, V. Donzella and K. Debattista</em>, in arXiv: 2404.05505, 2024</p>
    <a class="pdf" href="https://arxiv.org/pdf/2404.05505.pdf">PDF</a>
    <a class="code" href="https://github.com/hamedhaghighi/LidarGRIT">Code</a>
  </div>
  
  <div class="publication-item">
    <h3>Contrastive Learning-based Framework for Sim-to-Real Mapping of Lidar Point Clouds in Autonomous Driving Systems</h3>
    <p><em>H. Haghighi, A.Samadi, M. Dianati, V. Donzella and K. Debattista</em>, in arXiv: 2312.15817, 2023</p>
    <a class="pdf" href="https://arxiv.org/pdf/2312.15817.pdf">PDF</a>
    <a class="code" href="https://github.com/hamedhaghighi/CLS2R">Code</a>
  </div>
  
  <div class="publication-item">
    <h3>Accelerating Stereo Image Simulation for Automotive Applications Using Neural Stereo Super Resolution</h3>
    <p><em>H. Haghighi, M. Dianati, V. Donzella and K. Debattista</em>, IEEE Transaction on Intellignet Transportation Systems, 2023</p>
    <a class="pdf" href="https://doi.org/10.1109/TITS.2023.3287912">PDF</a>
    <a class="code" href="https://github.com/hamedhaghighi/ETSSR">Code</a>
  </div>
  
  <div class="publication-item">
    <h3>Review of the Learning-based Camera and Lidar Simulation Methods for Autonomous Driving Systems</h3>
    <p><em>H. Haghighi, X. Wang, H. Jing, M. Dianati</em>, arXiv: 2402.10079, 2024</p>
    <a class="pdf" href="https://arxiv.org/pdf/2402.10079.pdf">PDF</a>
  </div>
  
  <div class="publication-item">
    <h3>Automatic Evaluation of Crown Preparation using Image Processing Technique: A substitute to Faculty Scoring in Dental Education</h3>
    <p><em>Tahani, B.;Rashno, A.;Haghighi, H.; Kafieh, R.</em>, Journal of Medical Signals & Sensors, 2019</p>
    <a class="pdf" href="https://journals.lww.com/jmss/Fulltext/2020/10040/Automatic_Evaluation_of_Crown_Preparation_Using.3.aspx">PDF</a>
  </div>
</div>



<h2 class="section-header">Education</h2>

<div id="education" class="education">
  <div class="education-item">
    <h3>PhD in Engineering</h3>
    <p><strong>University of Warwick</strong>, [2020 - 2024], 
    Coventry, UK</p>
    <ul>
      <li><strong>Thesis</strong>: "Data-driven Simulation of Perception Sensors for Autonomous Vehicles"</li>
    </ul>
  </div>
  
  <div class="education-item">
    <h3>M.Sc. in Artificial Intelligence</h3>
    <p><strong>University of Tehran</strong>, [2016 - 2019], 
    Tehran, Iran</p>
    <ul>
      <li><strong>Thesis</strong>: "Ambient VAE: An Unsupervised Method for Image Restoration"</li>
    </ul>
    <ul>
      <li><strong>GPA</strong>: 18.85/20</li>
    </ul>
  </div>
  
  <div class="education-item">
    <h3>B.Sc. in Software Engineering</h3>
    <p><strong>Isfahan University of Technology</strong>, [2012 - 2016], Isfahan, Iran
    </p>
    <ul>
      <li><strong>GPA</strong>: 17.45/20</li>
    </ul>
  </div>
</div>


<h2 class="section-header">Contact</h2>
<div id="contact">
            <div>
                <h4>Email</h4>
                <p class="email">
                    Gmail: <a style="color: #007bff;" href="mailto:hamedlakers@gmail.com" target="_blank">hamedlakers@gmail.com</a><br>
                    UofW: <a style="color: #007bff;" href="mailto:hamed.haghighi@warwick.ac.uk" target="_blank">hamed.haghighi@warwick.ac.uk</a><br>                    
                </p>
            </div>
    <div class="row">
        <div class="seven columns">
            <iframe src="https://www.google.com/maps/embed/v1/place?key=AIzaSyBosd_ExVC7FQ-pX8BohIvZRZxBrGWZ-hQ&q=52.38339789842113, -1.5590910025789093" width="100%" height="420px" frameborder="0" style="border:0;"></iframe>
        </div>
            <div >
                <h4>Address</h4>
                <p class="address">
                    International Digital Laboratory (IDL), <br>
                    WMG, <br>
                    University of Warwick, <br>
                    Coventry, UK 
                </p>
            </div>
    </div>
</div>




<style>
  .navbar {
 position: fixed; /* Make navbar fixed */
  top: 0; /* Position at the top */
  width: 100%; /* Take up full width */
  overflow: hidden;
  background-color: #ffffff; 
  z-index: 1000; /* Ensure navbar is above other content */
   border-bottom: 1px solid #e0e0e0;
}

.navbar a {
  float: left;
  display: block;
  color: #333;
  text-align: center;
  padding: 14px 20px;
  font-size: 17px;
  text-decoration: none;
}

.navbar a:hover {
  background-color: #ddd;
  color: black;
}

.navbar a.active {
  background-color: #007bff;
  color: white;
}
  .section-header {
  font-size: 2em;
  font-weight: bold;
  color: #333;
  /* background-color: #f5f5f5; */
  padding: 10px 15px;
  border-radius: 5px;
  border-bottom: 2px solid #f2f2f2;
  margin-bottom: 20px;
  text-transform: uppercase;
}

.about-item{

  background-color: #f8f9fa; /* Light background color */
  border-radius: 8px; /* Rounded corners */
  padding: 20px; /* Padding around each item */
  margin-bottom: 30px; /* Spacing between items */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow for a lifted effect */
}
.project-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  align-items: stretch;
  background-color: #f8f9fa; /* Light background color */
  border-radius: 8px; /* Rounded corners */
  padding: 20px; /* Padding around each item */
  margin-bottom: 30px; /* Spacing between items */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow for a lifted effect */
}

.project-item {
  position: relative;
  overflow: hidden;
  cursor: pointer
}

.project-item img {
  width: 100%;
  height: 200px;
  object-fit: contain; /* Maintain aspect ratio */
  transition: transform 0.3s ease-in-out;
  border: 2px solid black; /* Add black border */
}

.project-info {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.8);
  color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
}

.project-item:hover img {
  transform: scale(1.1);
}

.project-item:hover .project-info {
  opacity: 1;
}

.project-info h3, .project-info p {
  margin: 10px;
  text-align: center;
}

.project-info p {
  font-size: 14px;
}

/*##############################publication */

.publications {
  margin-bottom: 80px; /* Adjust margin between publications */
}

.publication-item {
  margin-bottom: -30px; /* Adjust margin between items */
  background-color: #f8f9fa; /* Light background color */
  border-radius: 8px; /* Rounded corners */
  padding: 20px; /* Padding around each item */
  margin-bottom: 30px; /* Spacing between items */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow for a lifted effect */
}

.publication-item h3 {
  margin-bottom: 5px;
  color: #000066;
}

.publication-item p {
  margin-bottom: 5px;
}

.publication-item a {
  margin-right: 5px;
  text-decoration: none;
  color: #007bff;
}
.code{
  margin-right: 5px;
  text-decoration: none;
  color: #007bff;
  padding-left: 25px; /* Space for GitHub logo */
  background-image: url(../images/git-logo.png); /* GitHub logo as background */
  background-repeat: no-repeat;
  background-size: 20px 20px; /* Size of GitHub logo */
  background-position: left center; /* Position GitHub logo to the left of text */
}
.pdf{
  margin-right: 5px;
  text-decoration: none;
  color: #007bff;
  padding-left: 38px;
  background-image: url(../images/pdf-icon.jpg);
  background-repeat: no-repeat;
  background-size: 40px 20px;
  background-position: left center;
}
.publication-item a:hover {
  text-decoration: underline;
}

/* ########################education */
.education {
  margin-bottom: 50px;
}

.education-item {
  background-color: #f8f9fa; /* Light background color */
  border-radius: 8px; /* Rounded corners */
  padding: 20px; /* Padding around each item */
  margin-bottom: 30px; /* Spacing between items */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow for a lifted effect */
}

.education-item h3 {
  margin-bottom: 10px;
  font-size: 1.3em; /* Larger font size for degree */
  color: #000066; /* Degree text color */
}

.education-item p {
  margin-bottom: 15px;
  font-size: 1.1em; /* Font size for university and duration */
}

.education-item ul {
  list-style-type: none; /* Remove bullet points */
  margin-left: 0;
  padding-left: 0;
}

.education-item ul li {
  margin-bottom: 8px;
  font-size: 1em; /* Font size for thesis and GPA */
}

.education-item strong {
  font-weight: bold;
  color: #343a40; /* Text color for strong elements */
}

.education-item .gpa {
  color: #6c757d; /* GPA text color */
  font-size: 0.9em; /* Smaller font size for GPA */
  margin-top: 10px; /* Spacing between university and GPA */
}

/* ########################experience */
.experience {
  margin-bottom: 50px;
}

.experience-item {
  background-color: #f8f9fa; /* Light background color */
  border-radius: 8px; /* Rounded corners */
  padding: 20px; /* Padding around each item */
  margin-bottom: 30px; /* Spacing between items */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow for a lifted effect */
}

.experience-item h3 {
  margin-bottom: 10px;
  font-size: 1.3em; /* Larger font size for position */
  color: #000066; /* Position text color */
}

.experience-item p {
  margin-bottom: 15px;
  font-size: 1.1em; /* Font size for company, role, and date */
}

.experience-item ul {
  list-style-type: none; /* Remove bullet points */
  margin-left: 0;
  padding-left: 0;
}

.experience-item ul li {
  margin-bottom: 8px;
  font-size: 1em; /* Font size for bullet points */
}

.experience-item strong {
  font-weight: bold;
  color: #343a40; /* Text color for strong elements */
}

.experience-item a {
  color: #007bff; /* Link color */
  text-decoration: none; /* Remove underline */
}

.experience-item a:hover {
  text-decoration: underline; /* Underline on hover */
}

.experience-item em {
  font-style: italic; /* Italic style for author names */
}



#contact {
  background-color: #f8f9fa; /* Light background color */
  border-radius: 8px; /* Rounded corners */
  padding: 20px; /* Padding around each item */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow for a lifted effect */
}

#contact h4 {
    font-size: 1.5em; /* Larger font size for headings */
    /* margin-bottom: 15px; */
    color: #333; /* Dark text color */
}

#contact .email {
    margin-bottom: 20px;
}

#contact .address {
    font-style: italic;
}

/* Adjust the styling for the widgets to fit the Contact section */
#contact .widget {
    margin-bottom: 0px;
    border-bottom: 1px solid #e0e0e0; /* Optional: Add a subtle border between widgets */
    padding-bottom: 0px;
}

#contact .widget:last-child {
    border-bottom: none; /* Remove border for the last widget */
}

</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const projectItems = document.querySelectorAll('.project-item');

  projectItems.forEach(item => {
    const link = item.getAttribute('data-link');
    if(link)
    {
      item.addEventListener('mousedown', function() {
        window.open(link, '_blank');
    });
    }
  });

  const sections = ['about', 'experience', 'education', 'publications', 'projects', 'contact'];
  const navbar = document.querySelector('.navbar');
  const navLinks = navbar.querySelectorAll('a');

  window.addEventListener('scroll', function() {
    let currentSection = '';

    sections.forEach(section => {
      const element = document.getElementById(section);
      const offset = 200;

      if (element.offsetTop - offset <= window.scrollY && element.offsetTop + element.offsetHeight - offset > window.scrollY) {
        currentSection = section;
      }
    });

    navLinks.forEach(link => {
      link.classList.remove('active');
      if (link.getAttribute('href').substring(1) === currentSection) {
        link.classList.add('active');
      }
    });
  });
});
</script>