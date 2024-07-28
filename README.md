const madeIn = document.createElement('div');
madeIn.innerText = 'Made in JWT';
madeIn.style.position = 'fixed';
madeIn.style.left = '70px';
madeIn.style.bottom = '10px';
madeIn.style.display = 'none';
madeIn.style.backgroundColor = '#fff';
madeIn.style.border = '1px solid #ccc';
madeIn.style.borderRadius = '5px';
madeIn.style.padding = '10px';
madeIn.style.boxShadow = '0 0 10px rgba(0,0,0,0.1)';
document.body.appendChild(madeIn);

menuIcon.addEventListener('mouseenter', () => {
  if (window.innerWidth > 768) {
    madeIn.style.display = 'block';
  }
});

menuIcon.addEventListener('mouseleave', () => {
  madeIn.style.display = 'none';
});
