<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="LandingPage.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap" rel="stylesheet">
    <title>My Landing Page:</title>
</head>

<body>
    <header class="head1">
        <nav class="nav1">
            <div class="logo">
                <img id="logo" src="C:\Users\HP\Pictures\logo.jpg" alt="Image is Not Available" title="My Logo">
            </div>
            <div class="menu">

                <a href="#" id="tb1" class="tab">Home</a> 
                <a href="#" class="tab">About</a>
                <a href="#" class="tab">Services</a>
                <a href="#" class="tab">Job Seekers</a>

            </div>
            <div class="network">
                <i class="fa fa-facebook"></i>
                <i class="fa fa-google"></i>
                <i class="fa fa-twitter"></i>
                <!-- <a href="#">SignUp</a>
                <a href="#">SignIn</a> -->
            </div>
        </nav>
    </header>

    <div class="content">
        <h3 class="Subheading">CANDIDATE DEVELOPMENT</h3>
        <p class="para1">Result oriented training programs for job seekers and employees.</p>
        <p class="para2">Our training programs and campaigns are designed around specific professional development
            areas and are delivered to fit industry demands. Our training has been developed for individuals who
            need immediate skills development in key areas. Our aim is to maximize your learning and transferability
            of skills back to the workplace, while minimizing time off the job.</p>
    </div>
    <div class="form">
        <h3>Upload Your Resume</h3>
        <span>Full Name :<input type="text" placeholder="Enter your Full Name" /> </span>
        <span>Job profile :<input type="text" placeholder="Enter your Job Profile" /> </span>
        <span>Experience :<input type="number" /> </span>
        <span>Qualification :<input list="Class" />
            <datalist id="Class">
                <option> PHD </option>
                <option> Masters </option>
                <option> Bachelor </option>
                <option> HSC </option>
                <option> 10th or Below </option>
            </datalist> </span>
        <span>UPLOAD RESUME <input type="file" /> </span>
        <span> <input class="btn" id="b2" type="Reset" value="RESET FORM" /> </span>
        <span> <input class="btn" id="b1" type="submit" value="SUBMIT RESUME" />  </span>
    </div>
    
    <footer>
        <nav class="nav2">
            <div>
                <p>
                    <span>Contact Us</span> Address:- Sigma HR Solutions,Wagholi Pune.
                    Phone No:- 7234567890
                </p>
            </div>
    </footer>
</body>

</html>
