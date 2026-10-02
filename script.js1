function toggleTheme() {
  const body = document.body;
  body.classList.toggle("dark-mode");

  const btn = document.getElementById("btn-theme");
  if (body.classList.contains("dark-mode")) {
    btn.innerHTML = "☀️ Light Mode";
    localStorage.setItem("theme", "dark");
  } else {
    btn.innerHTML = "🌙 Dark Mode";
    localStorage.setItem("theme", "light");
  }
}
