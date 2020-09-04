<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>covid 19 information application</title>
    <link rel="stylesheet" href="bootstrap.css" />
    <style>
      .coral {
        color: coral;
      }
      h4 {
        font-family: Lobster;
      }

      .list-group li {
        padding: 0.2rem 1.5rem;
        padding-top: 1rem;
      }
      #country {
        background: coral;
        color: #fff;
      }
      .bgcoral {
        background: coral;
      }
      body {
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
        letter-spacing: 1px;
      }
    </style>
  </head>
  <body>
    
    <nav
      class="navbar navbar-expand-lg navbar-dark fixed-top"
      style="background: coral;"
    >
      <a class="navbar-brand">COVID 19</a>
      <button
        class="navbar-toggler"
        data-target="#my-nav"
        data-toggle="collapse"
        aria-controls="my-nav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="my-nav" class="collapse navbar-collapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="#">About</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="container mt-5 pt-4">
      <div class="row">
        <div class="col-12">
          <h4 class="h4">
            Covid 19 Information (Confirmed, Death, Recovered..etc).
          </h4>
        </div>
        <div class="col-12 col-md-6">
          <h5 class="h5 coral">Covid Global Informations.</h5>
          <div class="">
            <ul class="list-group">
              <li class="list-group-item active">
                <p class="">
                  Total Cases : <span class="total">498789454</span>
                </p>
              </li>
              <li class="list-group-item active">
                <p class="">
                  Total Deaths : <span class="deaths">498789454</span>
                </p>
              </li>
              <li class="list-group-item active">
                <p class="">
                   Recovered : <span class="recovered">498789454</span>
                </p>
              </li>
              <li class="list-group-item active">
                <p class="">
                   New Cases : <span class="newcases">498789454</span>
                </p>
              </li>
              <li class="list-group-item active">
                <p class="">
                   New Deaths : <span class="newdeaths">498789454</span>
                </p>
              </li>
            </ul>
          </div>
          <hr />
          <div class="select p-3">
            <label for="country">Choose a Country to show Info.</label>
            <select name="country" id="country" class="custom-select"> </select>
          </div>
        </div>
        <div class="col-12 col-md-6">
          <p class="font-weight-bold">
            Date : <span class="date coral"></span>
          </p>
          <hr />
          <p class="font-weight-bold">
            Information About Country
            <span class="text-primary coun">Afghanistan</span>
          </p>
          <hr />
          <ul class="list-group informations">
            <li class="list-group-item">
              <p>
                Total Cases :
                <span class="totalSingle p-1 badge-info">34544</span>
              </p>
            </li>
            <li class="list-group-item">
              <p>
                Total Deaths :
                <span class="deathsingle badge-danger p-1">24353</span>
              </p>
            </li>
            <li class="list-group-item">
              <p>
                Total Recovered :
                <span class="recoveredsingle badge-success p-1">333</span>
              </p>
            </li>
            <li class="list-group-item">
              <p>
                 New Cases :
                <span class="casesingle p-1 bgcoral text-white">444</span>
              </p>
            </li>
            <li class="list-group-item">
              <p>
                 New Deaths :
                <span class="newsingle p-1 bgcoral text-white">234</span>
              </p>
            </li>
            <li class="list-group-item">
                <p>
                     New Recovered :
                    <span class="newrecovered p-1 bgcoral text-white">234</span>
                </p>
            </li>
          </ul>
          <p class="lead mt-2">
            The Above Information is Updated on <span class="date"></span>
          </p>
        </div>
      </div>
    </div>
    <div class="container-fluid bgcoral p-3 mt-3">
      <div class="row">
        <div class="col-12 text-center text-white">
          powered By nir magar | &copy; 2020 all right reserved.
        </div>
      </div>
    </div>
<!-- <div class="container">
    <div class="row">
        <div class="col-8 mx-auto p-4">
            <kbd class="bg-info">
                hello
            </kbd>
            <hgroup>hello</hgroup>
          <progress ></progress>
          <output>aa</output>
          <summary>hello</summary>
          <mark class="p-1" style="background: var(--indigo);">ahhh good</mark>
        </div>
    </div>
</div> -->
    <script src="jquery.js"></script>
    <script src="proper.min.js"></script>
    <script src="bootstrap.min.js"></script>
    <script>
      var date = document.querySelectorAll(".date");
      let dat = new Date();
      dat = dat.toDateString();
      date.forEach(function (item) {
        item.innerHTML = dat;
      });
      console.log(dat);
      $(document).ready(function () {
        let options;
        $.ajax({
          url: "https://api.covid19api.com/summary",
          type: "GET",
          success: function (response) {
              console.log(response)
              $(".total").html(response.Global.TotalConfirmed);
              $(".deaths").html(response.Global.TotalDeaths);
              $(".recovered").html(response.Global.TotalRecovered);
              $(".newcases").html(response.Global.NewConfirmed);
              $(".newdeaths").html(response.Global.NewDeaths)
            for (var i = 0; i < response.Countries.length; i++) {
              options += `
                          <option value="${response.Countries[i].CountryCode}">${response.Countries[i].Country}</option>
                        `;
            }
            $("#country").html(options);
          },
        });
        $("#country").on("change", function () {
          var CountryCode = $(this).val();
          // console.log(countryCode)
          let informations;
          $.ajax({
            url: "https://api.covid19api.com/summary",
            type: "GET",
            success: function (response) {
              for (let i = 0; i < response.Countries.length; i++) {
                if (response.Countries[i].CountryCode === CountryCode) {
                  $(".totalSingle").html(response.Countries[i].TotalConfirmed);
                  $(".deathsingle").html(response.Countries[i].TotalDeaths);
                  $(".recoveredsingle").html(response.Countries[i].TotalRecovered);
                  $(".casesingle").html(response.Countries[i].NewConfirmed);
                  $(".newsingle").html(response.Countries[i].NewDeaths);
                  $(".newrecovered").html(response.Countries[i].NewRecovered);
                  $(".coun").html(response.Countries[i].Country);
                }
              }
              //   $(".informations").html(informations);
            },
          });
        });
      });
    </script>
  </body>
</html>

