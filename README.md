# css
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: Arial, sans-serif;
  background: #f4f4f4;
  text-align: center;
}

/* HEADER */

header{
  background: linear-gradient(90deg, #1b5e20, #43a047);
  color: white;

  padding: 40px 20px;
}

header h1{
  font-size: 55px;
}

header p{
  margin-top: 10px;
  font-size: 22px;
}

/* MENU */

nav{
  margin-top: 25px;
}

nav a{
  color: white;
  text-decoration: none;

  margin: 0 15px;

  font-size: 18px;
  font-weight: bold;
}

nav a:hover{
  text-decoration: underline;
}

/* HERO */

.hero{
  height: 80vh;

  display: flex;
  flex-direction: column;

  justify-content: center;
  align-items: center;

  background:
  linear-gradient(rgba(0,0,0,0.5),
  rgba(0,0,0,0.5)),

  url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854?q=80&w=1200&auto=format&fit=crop');

  background-size: cover;
  background-position: center;

  color: white;
}

.hero h2{
  font-size: 50px;
}

.hero p{
  margin: 20px 0;
  font-size: 22px;
}

/* BOTÃO */

button{
  padding: 15px 35px;

  border: none;
  border-radius: 10px;

  background: #43a047;
  color: white;

  font-size: 18px;
  cursor: pointer;
}

button:hover{
  background: #2e7d32;
}

/* SEÇÕES */

.section{
  padding: 80px 20px;
}

.section h2{
  font-size: 40px;
  color: #1b5e20;

  margin-bottom: 20px;
}

.section p{
  font-size: 20px;
}

/* CARDS */

.card-area{
  display: flex;

  justify-content: center;
  align-items: center;

  gap: 25px;

  flex-wrap: wrap;

  margin-top: 40px;
}

.card{
  background: white;

  width: 300px;

  padding: 30px;

  border-radius: 15px;

  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.card h3{
  color: #2e7d32;
  margin-bottom: 15px;
}

/* FOOTER */

footer{
  background: #1b5e20;
  color: white;

  padding: 25px;

  font-size: 18px;
}
