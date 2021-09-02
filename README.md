# animatedButton

Vi no IG do Sujeito Programador

<!DOCTYPE html>
<html lang="en">

<style>
body {
  background-color: black;
}
.container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 190px;
  height: 45px;
  text-decoration: none;
  color: white;
  background-color: rgb(0, 13, 128);
  font-size: 1.5rem;
  letter-spacing: 2px;
  overflow: hidden;
  font-family: sans-serif;
  border-radius: 2px;
}
span {
  position: relative;
  display: block;
  transition: 0.3s ease;
}

span::before {
  content: attr(data);
  position: absolute;
  transform: translateY(40px);
}

.container:hover span {
  transform: translateY(-40px);
  color: rgb(0, 255, 242);
}

.container span:nth-child(1) {
  transition-delay: 0.05s;
}

.container span:nth-child(2) {
  transition-delay: 0.15s;
}

.container span:nth-child(3) {
  transition-delay: 0.25s;
}

.container span:nth-child(4) {
  transition-delay: 0.35s;
}

.container span:nth-child(5) {
  transition-delay: 0.35s;
}

.container span:nth-child(6) {
  transition-delay: 0.25s;
}

.container span:nth-child(7) {
  transition-delay: 0.15s;
}


</style>
<body>
    <div class="container">
    <h1>Passe o mouse</h1>
        <a href="#">
            <span data="G">G</span>
            <span data="u">u</span>
            <span data="s">s</span>
            <span data="t">t</span>
            <span data="a">a</span>
            <span data="v">v</span>
            <span data="o">o</span>
        </a>
    </div>
</body>

</html>
