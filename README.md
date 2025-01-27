# FrontEnd
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Application Form</title>
    <style>
        body{
            background-color: #f4f4f9;
            font-family: 'Times New Roman', Times, serif;
            /* text-align: center; */
            justify-content: center;
            align-items: center;
            margin: 0;
            padding: 0;
            display: flex;
            height: 100vh;
        }

        .info{
            background: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 400px;
        }
        .info h1{
            text-align:justify;
            color: #333333;
        }
        .form label{
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #555555;
        }
        .form input{
            width: 100%;
            padding: 10px;
            border: 1px solid #cccccc;
            border-radius: 5px;
            font-size: 14px;
        }
        .form select{
            width: 100%;
            padding: 10px;
            border: 1px solid #cccccc;
            border-radius: 5px;
            font-size: 14px;
        }
        .form textarea{
            width: 100%;
            padding: 10px;
            border: 1px solid #cccccc;
            border-radius: 5px;
            font-size: 14px;
        }
        .form textarea{
            resize: none;
            height: 80px;
        }
        .submit-button {
            background-color: #4caf50;
            color: white;
            padding: 10px 15px;
            border-radius: none;
            cursor: pointer;
            font-size: 16px;
            width: 100%;
        }
        .submit-button:hover{
            background-color: #45a049;
        }
        .feedback{
            width: 100%;
            padding: 10px;
            border: 1px solid #cccccc;
            border-radius: 5px;
            font-size: 14px;
        }
        h2{
            text-align: center;
            margin-bottom: 20px;
            color: #333333;
        }
        .feedback label{
            width: 100%;
            padding: 10px;
            border: 1px solid #cccccc;
            border-radius: 5px;
            font-size: 14px;
        }
        .feedback textarea{
            width: 100%;
            padding: 10px;
            border: 1px solid #cccccc;
            border-radius: 5px;
            font-size: 14px;
        }
        .feedback textarea{
            resize: none;
            height: 60px;
        }
    </style>
</head>
<body>  
    <div class="info">
        <h1>Admission Application Form</h1>
            <form>
                <div class="form">
                    <label for="title">Title:</label>
                        <select id="title" name="title" required>
                            <option value="">Select</option>
                            <option value="Mr">Mr</option>
                            <option value="Ms">Ms</option>
                            <option value="Mrs">Mrs</option>
                            <option value="Dr">Dr</option>
                        </select>
                </div>
                <div class="form">
                    <label for="fullname">Name of Applicant:</label>
                    <input type="text" id="text" placeholder="Write your full name" required>
                </div>
                <div class="form">
                    <label for="text">Blood group:</label>
                        <select name="blood group" id="blood group">
                            <option value="">Select blood group</option>
                            <option value="O+">O+</option>
                            <option value="O+">O-</option>
                            <option value="O+">A+</option>
                            <option value="O+">A-</option>
                            <option value="O+">B+</option>
                            <option value="O+">B-</option>
                            <option value="O+">AB+</option>
                            <option value="O+">AB-</option>
                        </select>
                </div>
                <div class="form">
                    <label for="AAdhar number">Aadhar Number:</label>
                    <input type="number" id="number" placeholder="Enter your AAdhar Number" required>
                </div>
                <div class="form">
                    <label for="email">Email Id:</label>
                    <input type="email" id="email" placeholder="write your email id" required>
                </div>
                <div class="form">
                    <label for="payment">Payment Details</label>
                    <input type="text" id="payment" placeholder="Enter payment reference">
                </div>
                <div class="form">
                    <label for="course">Details of Course</label>
                    <input type="text" id="course" placeholder="Enter course details" required>
                </div>
                <div class="form">
                    <label for="department">Department</label>
                    <input type="text" id="department" placeholder="Enter department name">
                </div>
            <h2>Feedback Form</h2>
            <div class="feedback">
                <label for="feedback">Feedback:</label>
                <textarea id="feedback" name="feedback" placeholder="Write your feedback"></textarea>
            </div>
            <button type="submit" class="submit button">Submit</button>
            </form>
    </div>
</body>
</html>
