<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ভর্তি ফর্ম</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        h1 {
            font-size: 36px;
            margin: 0;
        }

        .form-container {
            max-width: 500px;
            margin: 50px auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .form-container h2 {
            text-align: center;
            color: #4CAF50;
            margin-bottom: 20px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .form-group input, .form-group select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        .form-group input:focus, .form-group select:focus {
            border-color: #4CAF50;
            outline: none;
        }

        .btn-submit {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 20px;
        }

        .btn-submit:hover {
            background-color: #45a049;
        }

        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>CHINADUKHURIA DIGITAL COACHING</h1>
        <p>ভর্তি ফর্ম</p>
    </header>

    <div class="form-container">
        <h2>ভর্তি ফর্ম পূরণ করুন</h2>
        <form action="submit_form.php" method="POST">
            <!-- Student Name -->
            <div class="form-group">
                <label for="student-name">নাম</label>
                <input type="text" id="student-name" name="student_name" placeholder="আপনার নাম লিখুন" required>
            </div>

            <!-- Father's Name -->
            <div class="form-group">
                <label for="father-name">বাবার নাম</label>
                <input type="text" id="father-name" name="father_name" placeholder="আপনার বাবার নাম লিখুন" required>
            </div>

            <!-- Class -->
            <div class="form-group">
                <label for="class">শ্রেণী</label>
                <select id="class" name="class" required>
                    <option value="">শ্রেণী নির্বাচন করুন</option>
                    <option value="3">৩</option>
                    <option value="4">৪</option>
                    <option value="5">৫</option>
                    <option value="6">৬</option>
                    <option value="7">৭</option>
                    <option value="8">৮</option>
                </select>
            </div>

            <!-- Mobile Number -->
            <div class="form-group">
                <label for="mobile">মোবাইল নম্বর</label>
                <input type="tel" id="mobile" name="mobile" placeholder="আপনার মোবাইল নম্বর লিখুন" required>
            </div>

            <!-- Submit Button -->
            <button type="submit" class="btn-submit">ভর্তি করুন</button>
        </form>
    </div>

    <footer>
        <p>&copy; 2024 Chinadukhuria Digital Coaching. All Rights Reserved.</p>
    </footer>
</body>
</html>
