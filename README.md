<!DOCTYPE html>
<html>

<head>
    
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="bg-container d-flex flex-column justify-content-center">
        <div class="container peace-page-container">
            <div class="row text-center pt-3">
                <h1 class="col-12 peace-page-heading">A Moment of Peace</h1>
                <p class="col-12 peace-page-description">
                    Turn off your phone, put on your headphones and take a moment for
                    yourself.
                </p>
                <hr class="col-10" />
                <h1 class="col-12 heading">
                    How long would you like your moment to be?
                </h1>
                <ul class="col-12 buttons-list-container d-flex flex-row justify-content-center">
                    <li><button id='twentySecondsBtn' class="button">20 Seconds</button></li>
                    <li><button id='thirtySecondsBtn' class="button">30 Seconds</button></li>
                    <li><button id='fortySecondsBtn' class="button">40 Seconds</button></li>
                    <li><button id='oneMinuteBtn' class="button">1 Minute</button></li>
                </ul>
                <p id='timerText' class="col-12 text-center"></p>
            </div>
        </div>
    </div>
    
</body>

</html>
