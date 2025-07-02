# josejohnphotography
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f5faff;
  color: #333;
}

header {
  background-color: #0077cc;
  color: white;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

header h1 {
  margin: 0;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 1rem;
}

.hero {
  background: url('images/hero.jpg') center/cover no-repeat;
  height: 60vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.7);
}

.hero h2 {
  font-size: 2.5rem;
}

section {
  padding: 2rem;
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
}

.gallery-grid img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

footer {
  background-color: #0077cc;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
