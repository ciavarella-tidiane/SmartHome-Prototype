// Sticky Header
window.addEventListener("scroll", function () {
  let header = document.querySelector("header");
  header.classList.toggle("scrolled", window.scrollY > 0);
});

// Mobile Menu Toggle
document
  .querySelector(".mobile-menu-icon")
  .addEventListener("click", function () {
    document.querySelector("nav ul").classList.toggle("active");
  });

// Back button
function goBack() {
  window.history.back();
}
