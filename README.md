# blinko-
Blinko Online Shopping Websites 

let cartCount = 0;

function addCart() {
  cartCount = cartCount + 1;
  document.getElementById("count").innerText = cartCount;
  alert("Product added to cart!");
}
