/* تنسيق عام للصفحة لضمان توسيط العناصر وتناسق الألوان */
body {
    font-family: 'Cairo', sans-serif;
    background-color: #f4f7f6;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
}

/* تنسيق حاوية نموذج تسجيل الدخول */
form, .login-container {
    background: #ffffff;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    width: 90%;
    max-width: 400px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

/* عنوان تسجيل الدخول */
h2 {
    text-align: center;
    color: #333;
    margin-bottom: 20px;
}

/* تنسيق حقول الإدخال */
input[type="text"],
input[type="password"] {
    width: 100%;
    padding: 12px;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-sizing: border-box;
    font-size: 14px;
}

/* تنسيق الأزرار */
button, input[type="submit"] {
    background-color: #4CAF50;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 8px;
    font-size: 16px;
    cursor: pointer;
    transition: background 0.3s ease;
}

button:hover, input[type="submit"]:hover {
    background-color: #45a049;
}

/* زر اتصل بنا أو الأزرار الإضافية */
.secondary-btn {
    background-color: #008CBA;
}

.secondary-btn:hover {
    background-color: #007bb5;
}
