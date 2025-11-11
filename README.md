# aromediningsolutions
Aromé Dining Solutions in Nyamirambo, Kigali, offers fine dining, catering, and corporate meals blending Rwandan and international cuisine. Founded by Ishimwe Dieudonné, it features 60 seats, VIP and outdoor areas, emphasizes quality, creativity, sustainability, local sourcing, and youth hospitality training.
<!doctype html>
<p class="muted">Vanilla panna cotta • Coffee & banana tart • Local fruit platter</p>
</div>
</div>
</section>


<section>
<h2>Gallery</h2>
<div class="gallery">
<div class="photo">Dining table setup</div>
<div class="photo">VIP lounge</div>
<div class="photo">Signature dish</div>
<div class="photo">Outdoor terrace</div>
</div>
</section>


<section>
<h2>Contact & Location</h2>
<div style="display:grid;grid-template-columns:1fr 1fr;gap:18px;align-items:start">
<div>
<p class="muted">Reserve: <strong style="color:var(--white)">+250 79 068 9888</strong><br/>Email: <a href="mailto:dieushimwa@gmail.com">dieushimwa@gmail.com</a><br/>WhatsApp: <a href="https://wa.me/250790689888">+250 79 068 9888</a></p>
<p class="muted">Map: Gisozi cafe ULK (use this as meeting landmark)</p>
<p class="muted">Address: Nyamirambo, Kigali (exact address provided during registration)</p>
</div>
<div class="map">
<iframe width="100%" height="220" frameborder="0" style="border:0" src="https://www.google.com/maps?q=Gisozi+cafe+ULK&output=embed" allowfullscreen aria-hidden="false" tabindex="0"></iframe>
</div>
</div>
</section>


</main>


<footer>
<div>
<div style="font-weight:700;color:var(--white)">Aromé Dining Solutions</div>
<div class="muted">Savor the Art of Dining • Nyamirambo, Kigali</div>
</div>
<div>
<a class="btn" href="https://www.aromediningsolutions.com">www.aromediningsolutions.com</a>
</div>
</footer>
</div>


<script>
function reserve(){
const name=document.getElementById('name').value||'Guest';
const phone=document.getElementById('phone').value||'+250790689888';
const email=document.getElementById('email').value||'dieushimwa@gmail.com';
const notes=document.getElementById('notes').value||'';
const message=`Reservation from ${name}%0APhone: ${phone}%0AEmail: ${email}%0ANotes: ${notes}`;
// open WhatsApp prefilled message
window.open('https://wa.me/250790689888?text='+encodeURIComponent(message),'_blank');
}
</script>
</body>
</html>
