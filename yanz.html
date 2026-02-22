<!DOCTYPE html>
<html>
<head>
<title>Pembayaran QRIS - Yanz Store</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
  font-family: Arial, sans-serif;
  text-align: center;
  color: white;
}

.container {
  margin-top: 20px;
}

h1 {
  color: #d400ff;
  text-shadow: 0 0 15px #d400ff;
}

.order-box {
  margin: 10px 0;
  font-size: 18px;
  color: #ff66ff;
}

.timer {
  font-size: 20px;
  margin-top: 10px;
  color: #ff4dff;
}

.qris {
  width: 260px;
  margin: 20px 0;
  border: 3px solid #d400ff;
  border-radius: 15px;
  box-shadow: 0 0 25px #d400ff;
}

input {
  padding: 10px;
  width: 80%;
  max-width: 300px;
  margin: 8px;
  border-radius: 8px;
  border: none;
}

button {
  padding: 12px 25px;
  background: #d400ff;
  border: none;
  color: white;
  border-radius: 8px;
  font-size: 16px;
  cursor: pointer;
  box-shadow: 0 0 10px #d400ff;
}

button:disabled {
  background: gray;
  cursor: not-allowed;
}
</style>
</head>
<body>

<div class="container">
  <h1>Yanz Store</h1>

  <div class="order-box">
    Nomor Order: <b id="orderId"></b>
  </div>

  <div class="timer">
    Sisa Waktu: <span id="countdown">05:00</span>
  </div>

  <p>Scan QRIS untuk membayar</p>

  <img src="https://image2url.com/r2/default/images/1771783420677-46b56842-783c-4292-9816-620dbec5087a.png" class="qris">

  <br>

  <input type="text" id="nama" placeholder="Masukkan Nama">
  <br>
  <input type="number" id="nominal" placeholder="Masukkan Nominal Pembayaran">
  <br>

  <button id="bayarBtn" onclick="kirimWA()">Saya Sudah Bayar</button>
</div>

<script>
// ===== NOMOR ORDER OTOMATIS =====
var order = "YZS" + Date.now();
document.getElementById("orderId").innerText = order;

// ===== TIMER 5 MENIT =====
var waktu = 300;
var countdownElement = document.getElementById("countdown");
var bayarBtn = document.getElementById("bayarBtn");

var timer = setInterval(function(){
  var menit = Math.floor(waktu / 60);
  var detik = waktu % 60;

  countdownElement.innerHTML =
    (menit < 10 ? "0" : "") + menit + ":" +
    (detik < 10 ? "0" : "") + detik;

  waktu--;

  if (waktu < 0) {
    clearInterval(timer);
    countdownElement.innerHTML = "WAKTU HABIS";
    bayarBtn.disabled = true;
    alert("Waktu pembayaran habis! Refresh halaman untuk buat order baru.");
  }
}, 1000);

// ===== KIRIM KE WHATSAPP =====
function kirimWA(){
  var nama = document.getElementById("nama").value;
  var nominal = document.getElementById("nominal").value;

  if(nama === "" || nominal === ""){
    alert("Isi nama dan nominal dulu!");
    return;
  }

  var pesan = 
  "Halo admin, saya sudah bayar.\n\n" +
  "Nomor Order: " + order + "\n" +
  "Nama: " + nama + "\n" +
  "Nominal: Rp" + nominal + "\n" +
  "Metode: QRIS";

  window.open("https://wa.me/6289501993267?text=" + encodeURIComponent(pesan), "_blank");
}
</script>

</body>
</html>