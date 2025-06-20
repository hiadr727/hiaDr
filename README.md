/* خطوط وأساسيات */
body {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(135deg, #1f1c2c, #928DAB);
  color: #f4f4f4;
}

/* العنوان */
h1 {
  text-align: center;
  font-size: 3em;
  color: #00FFC6;
  margin-top: 50px;
  text-shadow: 2px 2px 5px #000;
}

/* الحاوية */
.container {
  max-width: 800px;
  margin: auto;
  background-color: rgba(255, 255, 255, 0.05);
  padding: 30px;
  border-radius: 20px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
  backdrop-filter: blur(8px);
}

/* الأزرار */
button {
  padding: 15px 30px;
  border: none;
  border-radius: 50px;
  background: linear-gradient(45deg, #00C9FF, #92FE9D);
  color: #000;
  font-weight: bold;
  font-size: 1.2em;
  cursor: pointer;
  transition: 0.3s ease;
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

button:hover {
  transform: scale(1.05);
  background: linear-gradient(45deg, #f7971e, #ffd200);
}

/* روابط */
a {
  color: #FFA8A8;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* إطار صورة */
img
