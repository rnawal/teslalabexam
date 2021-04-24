<!DOCTYPE html>
<html lang="en" oncontextmenu="return false" ondragstart="return false">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exam | TESLA L@B</title>
  <meta content="" name="keywords">
  <meta content="" name="description">

  <!-- Favicons -->
  <link href="assets/img/favicon.png" sizes="16x16" type="image/png" rel="icon">
  <link href="assets/img/apple-touch-icon.jpg" rel="apple-touch-icon">

  <!-- Bootstrap CSS File -->
	<link href="/assets/lib/bootstrap/css/bootstrap.min.css" rel="stylesheet">

  <!-- Libraries CSS Files -->
  <link href="/assets/lib/animate/animate.min.css" rel="stylesheet">

  <!-- Main Stylesheet File -->
  <link href="/assets/css/style.css" rel="stylesheet">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,700,700i|Poppins:300,400,500,700" rel="stylesheet">
</head>

<body>

  <!--==========================
  Header
  ============================-->
  <header id="header" class="header-fixed">
    <div class="container">
      <div id="logo" class="pull-left" style="margin-top: -15px;">
        <a style="cursor: pointer;"><img src="/assets/img/final logo.png" alt="Tesla Lab Logo" /></img></a>
      </div>
      <nav id="nav-menu-container" class="btn-submit-top">
        <button class="mousetrap btn btn-info" disabled id="hsubmit" onclick="Next()">Next</button>
      </nav><!-- #nav-menu-container -->
    </div>
  </header><!-- #header -->
  <div id="timer" class="timer">
    <div class="container"><b><p id="time-left"></p></b></div>
  </div>

  <!--==========================
    Hero Section
  ============================-->
  <section id="hero">
    <div class="hero-container">
      <h1 class="ml11">
        <span class="text-wrapper">
          <span class="letters">Welcome to THE EXAM</span>
        </span>
      </h1>
      <a href="#exam" class="btn-get-started">Start</a>
    </div>
  </section><!-- #hero -->

  <!--==========================
    Exam Section
  ============================-->
  <section id="exam" class="mt-4">
    <div class="container">
      <div class="section-title text-center">
        <h2 class="mb-1">Exam Form</h2>
        <p>Tesla Lab</p>
      </div>
      <form action="javascript:void(0)" method="GET" role="form" class="php-email-form mt-4 mb-4" id="myForm">
        <h5 style="text-align: center;">Step 1 of 2</h5>
        <h3 style="text-align: center; margin-bottom: 30px;"><b>Participant's Info</b></h3>
        <div class="form-row">
          <div class="col-md-6 form-input form-input-1">
            <div class="form-group">
              <label for="name" style="padding-top: 18px;">Your Name</label>
              <span class="required"><b>*</b></span>
              <input readonly type="text" name="name" class="mousetrap form-control input" id="name" placeholder="Hint: Md. Sazzad Hossain Rupok" required />
            </div>
          </div>
          <div class="col-md-6 form-input form-input-2">
            <div class="form-group">
              <label for="email" style="padding-top: 18px;">Your Email</label>
              <span class="required"><b>*</b></span>
              <input readonly type="email" class="mousetrap form-control" name="email" id="email" placeholder="Hint: email@example.com" required style="display: block;" />
            </div>
          </div>
        </div>
        <div class="form-row">
          <div class="col-md-6 form-input form-input-1">
            <div class="form-group">
              <label for="phone" style="padding-top: 18px;">Contact Number</label>
              <span class="required"><b>*</b></span>
              <input readonly type="number" class="mousetrap form-control" name="phone" id="phone" placeholder="Hint: 01987654321" required style="display: block;" />
            </div>
          </div>
          <div class="col-md-6 form-input form-input-2">
            <div class="form-group">
              <label for="institute" style="padding-top: 18px;">Institution</label>
              <span class="required"><b>*</b></span>
              <input readonly type="text" class="mousetrap form-control" name="institute" id="institute" placeholder="Hint: Saint Joseph Higher Secondary School" required style="display: block;" />
            </div>
          </div>
        </div>
        <div class="form-row">
          <div class="col-md-6 form-input form-input-1">
            <div class="form-group" style="padding-top: 18px;">
              <div class="category radio mousetrap" style="font-size: 14px;">
                <label for="category" style="font-size: 16px;">Category: </label>
                <span class="required"><b>*</b></span>
                <select disabled class="mousetrap" name="category" id="category" style="width: 100%; padding-left: 7px; padding-top: 10px; padding-bottom: 10px; font-size: 14px; opacity: 60%; cursor: pointer; border-radius: 5px;">
                  <option selected disabled style="opacity: 60%;" class="mousetrap" value="Select">Select
                  <option style="opacity: 60%;" class="mousetrap" value="Primary">Primary
                  <option style="opacity: 60%;" class="mousetrap" value="Junior">Junior
                  <option style="opacity: 60%;" class="mousetrap" value="Secondary">Secondary
                  <option style="opacity: 60%;" class="mousetrap" value="Higher_Secondary">Higher Secondary
                </select>
              </div>
            </div>
          </div>
          <div class="col-md-6 form-input form-input-2">
            <div class="form-group" style="padding-top: 18px;">
              <div class="class radio mousetrap" style="font-size: 14px;">
                <label for="class">Grade (Must Be Same As The Registration Form)</label>
                <span class="required"><b>*</b></span>
                <select disabled class="mousetrap" name="class" style="width: 100%; padding-left: 7px; padding-top: 10px; padding-bottom: 10px; font-size: 14px; opacity: 60%; cursor: pointer; border-radius: 5px;" id="class">
                  <option selected disabled style="opacity: 60%;" class="mousetrap" value="Select">Select
                  <option style="opacity: 60%;" class="mousetrap" value="KG">KG
                  <option style="opacity: 60%;" class="mousetrap" value="1">1
                  <option style="opacity: 60%;" class="mousetrap" value="2">2
                  <option style="opacity: 60%;" class="mousetrap" value="3">3
                  <option style="opacity: 60%;" class="mousetrap" value="4">4
                  <option style="opacity: 60%;" class="mousetrap" value="5">5
                  <option style="opacity: 60%;" class="mousetrap" value="6">6
                  <option style="opacity: 60%;" class="mousetrap" value="7">7
                  <option style="opacity: 60%;" class="mousetrap" value="8">8
                  <option style="opacity: 60%;" class="mousetrap" value="9">9
                  <option style="opacity: 60%;" class="mousetrap" value="10">10
                  <option style="opacity: 60%;" class="mousetrap" value="SSC">SSC
                  <option style="opacity: 60%;" class="mousetrap" value="Other">Other
                </select>
              </div>
            </div>
          </div>
        </div>
        <div id="GradeDiv" class="form-row" style="margin-bottom: 15px!important;">
          <input readonly type="text" style="text-align: center;" name="grade" class="mousetrap form-control" id="grade" placeholder="Grade *" style="display: block;" />
        </div>
        <div class="text-center">
          <input type="submit" class="mousetrap btn btn-info" disabled id="submit" name="Token" value="Next" />
        </div>
      </form>

    </div>
  </section><!-- End Exam Section -->
    
  <!--==========================
  Footer
  ============================-->
  <footer id="footer">
    <div class="container">
      <div class="copyright">
        &copy; Copyright <strong>TESLA LAB</strong>. All Rights Reserved
      </div>
      <div class="credits">
        Developed by S.M. RANA NAWAL
      </div>
    </div>
  </footer><!-- #footer -->

  <!-- JavaScript Libraries -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-migrate/3.3.2/jquery-migrate.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-validate/1.19.0/jquery.validate.min.js"></script>
  <script src="/assets/js/mousetrap.min.js"></script>
  <script src="/assets/js/shortcut.js"></script>
  <script src="/assets/lib/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="/assets/lib/easing/easing.min.js"></script>
  <script src="/assets/lib/wow/wow.min.js"></script>
  <script src="/assets/lib/waypoints/waypoints.min.js"></script>
  <script src="/assets/lib/superfish/hoverIntent.js"></script>
  <script src="/assets/lib/superfish/superfish.min.js"></script>
  <script>
    $(document).ready(function() {
      $("#myForm").validate();
    });
  </script>
  <script>
    function Next() {
      $("#submit").trigger('click');
    }
  </script>
  <script>
    var countDownDate = new Date("Apr 24, 2021 20:00:00").getTime(); // Adjust the time and date based on exam starting time
    var x = setInterval(function() {
      var now = new Date().getTime();
      var distance = countDownDate - now;
      var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      var seconds = Math.floor((distance % (1000 * 60)) / 1000);
      document.getElementById("time-left").innerHTML = "Exam Is Starting After:- " + hours + "H " + minutes + "M " + seconds + "S";
      if (distance < 0) {
        clearInterval(x);
        document.getElementById("time-left").innerHTML = "Exam Has Started!";
        document.getElementById("hsubmit").removeAttribute('disabled');
        document.getElementById("submit").removeAttribute('disabled');
        document.getElementById("name").removeAttribute('readonly');
        document.getElementById("email").removeAttribute('readonly');
        document.getElementById("phone").removeAttribute('readonly');
        document.getElementById("institute").removeAttribute('readonly');
        document.getElementById("grade").removeAttribute('readonly');
        document.getElementById("class").removeAttribute('disabled');
        document.getElementById("category").removeAttribute('disabled');
      }
    }, 1000);
  </script>
  <script>
    $("#class").change(function() {
      if ($(this).val() == "Other") {
        $('#GradeDiv').show();
        $('#grade').attr('required', '');
      } else {
        $('#GradeDiv').hide();
        $('#grade').removeAttr('required');
      }
    });
    $("#class").trigger("change");

    $("#category").change(function() {
      if ($(this).val() == "Primary") {
        $('#myForm').attr('action', 'questions/Primary');
      }
      if ($(this).val() == "Junior") {
        $('#myForm').attr('action', 'questions/Junior');
      }
      if ($(this).val() == "Secondary") {
        $('#myForm').attr('action', 'questions/Secondary');
      }
      if ($(this).val() == "Higher_Secondary") {
        $('#myForm').attr('action', 'questions/Higher_Secondary');
      }
      if ($(this).val() == "Select") {
        $("submit").attr('disabled', '');
        $('#myForm').removeAttr('action', 'javascript:void(0)');
      }
    });
    $("#category").trigger("change");
  </script>

  <!-- Template Main Javascript File -->
  <script src="/assets/js/main.js"></script>

  <!-- Font Awesome Kit -->
  <script src="https://kit.fontawesome.com/8b59f9c63b.js" crossorigin="anonymous"></script>

</body>
</html>
