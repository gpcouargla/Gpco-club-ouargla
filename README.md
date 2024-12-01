<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>التسجيل في نادي الجيوفيزياء</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 500px;
            margin: 50px auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h2 {
            text-align: center;
            color: #333;
        }
        label {
            display: block;
            margin: 15px 0 5px;
            color: #555;
        }
        input, select, textarea, button {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }
        button {
            background-color: #007BFF;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>استمارة التسجيل في نادي الجيوفيزياء</h2>
        <form>
            <label for="name">الاسم واللقب</label>
            <input type="text" id="name" name="name" required>

            <label for="registration">رقم التسجيل</label>
            <input type="text" id="registration" name="registration" required>

            <label for="field">الميدان</label>
            <input type="text" id="field" name="field" required>

            <label for="phone">رقم الهاتف</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="email">البريد الإلكتروني</label>
            <input type="email" id="email" name="email" required>

            <label for="gender">الجنس</label>
            <select id="gender" name="gender">
                <option value="male">ذكر</option>
                <option value="female">أنثى</option>
            </select>

            <label for="benefit">ماذا يمكن الاستفادة من النادي؟</label>
            <textarea id="benefit" name="benefit" rows="4"></textarea>

            <button type="submit">تأكيد</button>
        </form>
    </div>
</body>
</html>
