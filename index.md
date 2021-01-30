---
author_profile: true
---

<style>
html {
  font-size: 18px;
}

/* This is not a good way of doing this */
.fa-fw, fab, fas {
    /* set all icons to white-ish */
    color: #eaeaec!important
}

.sidebar {
    /* set opacity of sidebar to always be 1 */
    opacity: 1!important
}

h3 {
    margin: 1em 0 0.5em 0;
}

.card h3 {
  margin-top: 0;
}

p {
  margin: 0 0 0.5em 0!important;
}

ul li {
  margin-bottom: 0;
}

hr.mid {
  width: 60%;
}


/* Remove extra left and right margins, due to padding */
.row {margin: 0 -5px;}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.floatleft {
  float: left;
}

.floatright {
  float: right;
  margin-top: 5px; /* this is a little hacky, but is anything on this page not hacky? */
}

/* Float 3 columns side by side */
.col2 {
  float: left;
  width: 45%;
  padding: 0 10px;
  margin-top: 10px!important;
  margin-bottom: 0!important;
}

.leftcol {
  margin-left: 4%!important;
  margin-right: 1%!important;
}

.rightcol {
  margin-left: 1%!important;
  margin-right: 4%!important;
}

.card {
  padding: 16px;
  margin: 10px 0 0 0;
  background-color: transparent;
  border: 2px solid #51555d;
  border-radius: 5px;

}

.card img {
    float: left;
    margin: 0 10px 0 0;
    width: 150px;
    border-radius: 5px;
}

.card h3 a {
    color: #eaeaea;
    text-decoration: none;
}

.card h3 a:hover {
    text-decoration: none!important;
}

.undline {
  transition: 300ms;
  border-bottom: 2px solid transparent;
}

.undline:hover {
  border-color: #eaeaea;
}

.clearfix:before,
.clearfix:after {
    content: " ";
    display: table;
}

.clearfix:after {
    clear: both;
}

.clearfix {
    zoom: 1;
}
</style>

# Jolon Behrent

## Projects

<!-- <div class="card clearfix">
<h3><a class="undline" href="https://github.com/JolonB/">Card Example</a></h3>

<img src="assets/img/img.png"/>

<p>
Fill this in. <i class="fas fa-fw fa-hammer"></i>
</p>
</div> -->

<div class="card clearfix">
<h3><a class="undline" href="assets/pdf/final_report.pdf">IoT Environmental Monitoring - Honours Project</a></h3>

<img src=""/>

<p>
My honours project involved working with <a href="https://benjamin.secker.nz">Benjamin Secker</a> to develop an Internet of Things environmental monitoring solution for the Greater Wellington Regional Council. I was tasked with developing the hardware and the low-level software.
</p>
<p>
The project was large in scope but came close to being finished by the end of the 8-month time frame. The device was capable of reliably reading data from SDI-12 sensors then saving it to an SD card and sending it to a cloud backend. There's too much to write about in this little box, so if you want to read more about it, you can find the final report <a href="assets/pdf/final_report.pdf">here</a>.
</p>
</div>

<div class="card clearfix">
<h3><a class="undline" href="https://github.com/JolonB/Home-Security">Home Security System</a></h3>

<img src="assets/img/hal_camera.svg"/>

<p>
I've set up a security system before but found that it was finicky and was missing a lot of important features. The better security systems are more expensive and often involve a third-party. This open-source project is for an end-to-end IoT home security system that can send text/email notifications to approved users and allow them to view footage captured by WiFi-connected nodes throughout their house. Each node is a custom-made device built on an ESP32 with the ability to be powered by battery and from mains. This is currently a work in progress.
</p>
</div>

<div class="card clearfix">
<h3><a class="undline" href="https://github.com/JolonB/SDI12-UART">UART to SDI-12 Conversion</a></h3>

<img src="assets/img/sdi.png"/>

<p>
SDI-12 is a wired communication protocol used for low-powered, environmental sensors. Unfortunately, I was unable to find any open-source hardware implementation of this protocol, so I needed to create something myself. The circuit I designed allows for conversion between UART and SDI-12, which means almost any microcontroller can communicate with an SDI-12 sensor (with the proper software implementation).
</p>
</div>

<div class="card clearfix">
<h3><a class="undline" href="https://github.com/JolonB/RabbitGenetics">Rabbit Genetic Simulation</a></h3>

<img src="assets/img/rabbit.png"/>

<p>
I saw <a href="https://www.youtube.com/watch?v=r_It_X7v-1E">this video</a> a few years ago and it inspired me to create something just like it. In short, it a rabbit simulations which allows them to produce offspring that have traits of the parents. I didn't want to refer to the video while I was designing this, so whatever I've done (good or bad) was purely my decision. This project is built using Java and Gradle. Unfortunately, it was never finished and maybe never will be.
</p>
</div>

<div class="card clearfix">
<h3><a class="undline" href="https://github.com/JolonB/Latex-Cover-Letter">LaTeX Cover Letter Template</a></h3>

<img src="assets/img/template.png"/>

<p>
For all my previous job applications, I had written my cover letters in Word. Since they were all styled in exactly the same way, I figured I could start making them in LaTeX instead. This template is almost an exact copy of the one I made years ago in Word, except now it comes with custom commands so text can be filled in automatically.
</p>
</div>

## Experience
### Summer Research Assistant

*Robinson Research Institute, Lower Hutt*  
*November 2, 2020 - March 5, 2021*

Tasks:

- Designing electronic circuit for thruster.
- Collecting data.

Languages Used:

- MATLAB

<hr class="mid">

### Embedded Software Developer/Tester

*Aviat Networks, Lower Hutt*  
*November 18, 2019 - February 21, 2020*

Tasks:

- Writing code for embedded radio system.
- Manual testing.
- Writing automated tests.
- Working in Agile team.

Languages Used:

- C/C++
- Python
- Bash

<hr class="mid">

### Junior Design Engineer

*Tait Communications, Christchurch*  
*November 19, 2018 - February 8, 2019*

Tasks:

- Developing tool with user interface to calculate intermodulation distortion.

Languages Used:

- Java
- Python

## Skills

<div class="row">
  <div class="card col2 leftcol"><span class="floatleft">Python</span><i class="fab fa-python floatright"></i></div>
  <div class="card col2 rightcol"><span class="floatleft">C/C++</span><i class="fas fa-code floatright"></i></div>
</div>
<div class="row">
  <div class="card col2 leftcol"><span class="floatleft">Java</span><i class="fab fa-java floatright"></i></div>
  <div class="card col2 rightcol"><span class="floatleft">MATLAB</span><!--i class="fas fa-square-root-alt floatright"></i--></div>
</div>
<div class="row">
  <div class="card col2 leftcol"><span class="floatleft">Circuit Design</span></div>
  <div class="card col2 rightcol"><span class="floatleft">Mechatronics</span></div>
</div>
<div class="row">
  <div class="card col2 leftcol"><span class="floatleft">Microcontrollers</span></div>
  <div class="card col2 rightcol"><span class="floatleft">Linux</span><i class="fab fa-linux floatright"></i></div>
</div>
<div class="row">
  <div class="card col2 leftcol"><span class="floatleft">Git</span><i class="fab fa-git-alt floatright"></i></div>
  <div class="card col2 rightcol"><span class="floatleft">Agile</span><!--i class="fas fa-project-diagram floatright"></i--></div>
</div>
<div class="row">
  <div class="card col2 leftcol"><span class="floatleft">AI</span><!--i class="fas fa-brain floatright"></i--></div>
  <div class="card col2 rightcol"><span class="floatleft">Statistics</span><!--i class="fas fa-calculator floatright"></i--></div>
</div>

## Education

### University

*Victoria University of Wellington*  
Bachelor of Engineering with First Class Honours  
Electronic and Computer Systems Engineering  
2017 - 2020  
Average grade: A+

### College

*Saint Patrick's College*  
Silverstream  
2012 - 2016

## Resume

You can find my resume [here](assets/pdf/JolonBehrent_CV.pdf). I'll do my best to keep it up to date, though most of the details are the same as on this page.