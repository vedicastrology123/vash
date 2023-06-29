---
title: "Horoscope Prediction"
descslug: "Horoscope Prediction"
date: 2020-04-07T12:52:36+06:00
image: "images/success.jpg"
author: Steve Hora
description : "Horoscope Prediction by Steve Hora"
type: "post"
categories: 
  - "Vedic Astrology"
tags:
  - "Birth Chart Predictions"
  - "Mundane Predictions"
lead: Vedic Astrology by Steve Hora
lastmod: latest 
path:
  - "https://stevehora.com/articles/gform/"
keywords:
  - "Predictions"
  - "Steve Hora"
  - "Quora"
  - "Q2A"
  - "Question and Answers"
  
news_keywords:
  - "Vedic Astrology"
  - "Steve Hora"

structured:
  type: "article"

article:
  image:
   author: "Steve Hora"
   src: "images/vaashicon.png"
   height: 60
   width: 60
  
---
{{< rawhtml >}}
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Vedic Astrology</title>
 <style>
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.2); /* Black w/ opacity */
}

.modal-content {
  opacity: 1.0;
  background-color: rgb(0, 0, 0);
  background-color: #ffffff;
  margin: 1% auto; /* 15% from the top and centered */
  padding: 5px;
  border: 1px solid #888;
  width: 35%; /* Could be more or less, depending on screen size */
}
 </style>
<script type="text/javascript">
function openPopup(){
//alert(" Alert inside my_code function
var modal = document.getElementById("modal");
  modal.style.display = "block";

     document.getElementById("modal-content").innerHTML='<object type="text/html" data="gform.html" ></object>';
	 //window.location.hash = 'openModal';
}

window.onload=openPopup;
</script>

 <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
 <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.form/4.2.2/jquery.form.min.js" integrity="sha256-2Pjr1OlpZMY6qesJM68t2v39t+lMLvxwpa8QlRjJroA=" crossorigin="anonymous"></script>

<script type="text/javascript">
$('#bootstrapForm').submit(function (event) {
    event.preventDefault()
    var extraData = {}
    {
        /* Parsing input date id=696506756 */
        var dateField = $("#696506756_date").val()
        var timeField = $("#696506756_time").val()
        let d = new Date(dateField)
        if (!isNaN(d.getTime())) {
            extraData["entry.696506756_year"] = d.getFullYear()
            extraData["entry.696506756_month"] = d.getMonth() + 1
            extraData["entry.696506756_day"] = d.getUTCDate()
        }
        if (timeField && timeField.split(':').length >= 2) {
            let values = timeField.split(':')
            extraData["entry.696506756_hour"] = values[0]
            extraData["entry.696506756_minute"] = values[1]
        }
    }
    {
        // Parsing input time id=5948105
        var field = $("#5948105").val()
        if (field) {
            var values = field.split(':')
            extraData["entry.5948105_hour"] = values[0]
            extraData["entry.5948105_minute"] = values[1]
            extraData["entry.5948105_second"] = values[2]
        }
    }
    $('#bootstrapForm').ajaxSubmit({
        data: extraData,
        dataType: 'jsonp',  // This won't really work. It's just to use a GET instead of a POST to allow cookies from different domain.
        error: function () {
            // Submit of form should be successful but JSONP callback will fail because Google Forms
            // does not support it, so this is handled as a failure.
            alert('Form Submitted. Thanks.')
            // You can also redirect the user to a custom thank-you page:
            // window.location = 'http://www.mydomain.com/thankyoupage.html'
        }
    })
})
</script>
</head>
<body>
<div id="modal" class="modal">
<div id="openModal" class="modal-content">
<form action="https://docs.google.com/forms/d/e/1FAIpQLScEenBYOmwO_jb-QvETuyTjOBEaSyl8sRApMQFq9khTFrDRCQ/formResponse"
      target="_self"
      id="bootstrapForm"
      method="POST">
    <fieldset>
        <h2>Input Form<br><small></small></h2>
    </fieldset>
    <fieldset>
        <legend for="">Email</legend>
        <div class="form-group">
            <input id="emailAddress" type="email" name="emailAddress" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "short" id: "855228724" -->
    <fieldset>
        <legend for="855228724">Name</legend>
        <div class="form-group">
            <input id="1350257766" type="text" name="entry.1350257766" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "date" id: "2110027162" -->
    <fieldset>
        <legend for="2110027162">Date of Birth</legend>
        <div class="form-group">
            <input type="date" id="696506756_date" placeholder="6/18/2023" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "time" id: "498408220" -->
    <fieldset>
        <legend for="498408220">Time of Birth</legend>
        <div class="form-group">
            <p class="help-block">Be clear about AM. After midnight it is AM, next day date. And PM is after mid-noon till midnight.</p>
            <input type="time" id="5948105" placeholder="9:04:27 AM" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "short" id: "705894835" -->
    <fieldset>
        <legend for="705894835">Place of Birth - Town, City, Country</legend>
        <div class="form-group">
            <p class="help-block">Give the nearest town, City, State and Country</p>
            <input id="597702208" type="text" name="entry.597702208" class="form-control" required>
        </div>
    </fieldset>


    <!-- Field type: "paragraph" id: "1974123443" -->
    <fieldset>
        <legend for="1974123443">One Life Question for Prediction</legend>
        <div class="form-group">
            <p class="help-block">Ask specific question e.g.: When I will get married?</p>
            <textarea id="1512043858" name="entry.1512043858" class="form-control" required></textarea>
        </div>
    </fieldset>


    <!-- Field type: "section" id: "964873817" -->
    <fieldset>
        <legend for="964873817"></legend>
        <div class="form-group">
        </div>
    </fieldset>


    <!-- Field type: "checkboxes" id: "603292669" -->
    <fieldset>
        <legend for="603292669">Please pay Guru Dakshina with secure payment gateway</legend>
        <div class="form-group">
            <div class="checkbox">
                <label>
                    <input type="checkbox" name="entry.883185347" value="₹ 300" required>
                    ₹ 300
                </label>
            </div>
        </div>
    </fieldset>

    <input type="hidden" name="fvv" value="1">
    <input type="hidden" name="fbzx" value="-6238198222619838537">
    <!--
        CAVEAT: In multipages (multisection) forms, *pageHistory* field tells to google what sections we've currently completed.
        This usually starts as "0" for the first page, then "0,1" in the second page... up to "0,1,2..N" in n-th page.
        Keep this in mind if you plan to change this code to recreate any sort of multipage-feature in your exported form.
        We're setting this to the total number of pages in this form because we're sending all fields from all the section together.
    -->
    <input type="hidden" name="pageHistory" value="0,1">

    <input class="btn btn-primary" type="submit" value="Submit">
</form>
</div>
</div>
</body>
</html>

{{< /rawhtml >}}