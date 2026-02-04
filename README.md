* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background: #0b0b0b;
  color: #fff;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 18px 40px;
  background: #111;
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

.logo span {
  color: #4f8cff;
}

nav a {
  color: #fff;
  margin-left: 25px;
  text-decoration: none;
  font-weight: 500;
}

.hero {
  text-align: center;
  padding: 90px 20px;
  background: linear-gradient(135deg, #4f8cff, #7a00ff);
}

.hero h1 {
  font-size: 36px;
  margin-bottom: 15px;
}

.hero p {
  font-size: 16px;
  margin-bottom: 25px;
}

.hero button {
  padding: 12px 30px;
  border: none;
  border-radius: 25px;
  background: #fff;
  color: #000;
  font-weight: bold;
  cursor: pointer;
}

.games {
  padding: 50px 30px;
}

.games h2 {
  margin-bottom: 25px;
}

.game-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 20px;
}

.game {
  background: #1a1a1a;
  padding: 25px;
  border-radius: 12px;
  text-align: center;
  cursor: pointer;
  transition: 0.3s;
}

.game:hover {
  background: #4f8cff;
}

footer {
  text-align: center;
  padding: 25px;
  background: #111;
  margin-top: 50px;
}
