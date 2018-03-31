# CMS

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>

    <style>
        .bg {
            background-color: #e9ecef;
        }
    </style>
</head>

<body class="bg ">

    <div class="container-fluid jumbotron">
            
        <div class="text-center">
            <img src="./cigna.png" class="rounded " alt="cigna logo">
        </div>
        <br/>
        <h1 class="text-center">Cigna CMS Workflow</h1>
        <br/>
        <div class="container col-4">
            <form action="/action_page.php">
                <div class="form-group font-weight-bold">
                    <label for="loginid">Login ID:</label>
                    <input type="loginid" class="form-control" id="loginid" placeholder="Enter loginid" name="email">
                </div>
                <div class="form-group font-weight-bold">
                    <label for="pwd">Password:</label>
                    <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd">
                </div>
                <button type="submit" class="btn btn-primary">Sign In</button>
            </form>
        </div>
    </div>


</body>

</html>
