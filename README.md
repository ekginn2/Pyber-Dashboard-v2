<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Bootstrap Visualization Dashboard - Pyber Analysis</title>

    <!-- Bootstrap CDN -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
    <!-- External CSS -->
    <link rel="stylesheet" href="marketing.css">

  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

  </head>

  <body>

    <nav class="navbar navbar-default">

      <div class="container-fluid">

        <!-- Brand and toggle get grouped for better mobile display -->
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" >
          </button>

          <a class="navbar-brand" href="landing.html">Pyber</a>
        </div>

        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="navbar-collapse">
          <ul class="nav navbar-nav navbar-right">
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Plots<span class="caret"></span></a>
              <ul class="dropdown-menu">
                <li><a href="bubble.html">Rides vs Fares</a></li>
                <li><a href="drivers.html">Pyber Drivers</a></li>
                <li><a href="fares.html">Pyber Fares</a></li>
                <li><a href="rides.html">Pyber Rides</a></li>
                <li role="separator" class="divider"></li>
              </ul>
            </li>
            <li><a href="comparisons.html">Comparison</a></li>
            <li><a href="data.html">Data</a></li>
          </ul>
        </div>

        <!-- /.container-fluid -->
      </div>
      <!-- /.navbar-collapse -->
    </nav>

  <div class="container">


    <div class="row">
      <div class="col-md-12">
        <h1>Pyber Analysis</h1>
      </div>
    </div>


    <div class="row">

     <div class="col-md-7">
       <h2>Summary: Opportunities in the Ride-Sharing Market</h2>
       <hr>
       <br><br>
     </div>

     <div class="col-md-5" align = "right">
       <h2>Visualizations</h2><br>
       <hr>
     </div>

    </div>

    <div class="row">

     <div class="col-md-7">
       <p>
         <img src="pyberbubble.png" alt="Pyber Bubble Chart" height="300" align="left">
         The purpose of this project was to analyze the relationship between four key variables:
         average fare per city, total number of rides per city, total number of drivers per city, and the city type (urban, suburban, or rural).
         The dataset contained information about each of Pyber's active driver and historic rides, including details like city, driver count, individual fares, and city type.
         <br><br>To accomplish this, I used pandas and numpy to build the dataset and parse it into readable dataframe. I then used matplotlib to plot various aspects of the data,
         namely the trends for rides, drivers, and fares in different city types. This site provides the source data and visualizations created as part of the analysis,
          as well as descriptions of any correlations observed.
      </p>
     </div>

     <div class="col-md-5">
       <a href="bubble.html"> <img src="pyberbubble.png" alt="Pyber Bubble Chart" height="200" align = "right"></a>
       <a href="drivers.html"> <img src="pyberdrivers.png" alt="Pyber Drivers" height="200" align = "right"></a>
       <a href="rides.html"> <img src="pyberrides.png" alt="Pyber Rides" height="200" align = "right"></a>
       <a href="fares.html"> <img src="pyberfares.png" alt="Pyber Fares" height="200" align = "right"></a>

     </div>

    </div>

  </div>

<h4>Erica Rosa <br>
GT Coding Bootcamp 2018</h4>
  </body>

</html>
