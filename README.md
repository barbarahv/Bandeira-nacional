# Bandeira-nacional
A bandeira nacional feita em java


<canvas width="600" height="400"></canvas>

<script>
	
 var tela = document.querySelector('canvas');
 var pincel = tela.getContext('2d');

 pincel.fillStyle = 'darkgreen';
 pincel.fillRect(0, 0, 600, 400);

 pincel.fillStyle = 'yellow';
 pincel.beginPath();
 pincel.moveTo(300, 50);
 pincel.lineTo(50, 200);
 pincel.lineTo(550, 200);
 pincel.fill()


 pincel.fillStyle = 'yellow';
 pincel.beginPath();
 pincel.moveTo(300, 350);
 pincel.lineTo(50, 200);
 pincel.lineTo(550, 200);
 pincel.fill()


 pincel.fillStyle = 'darkblue';
 pincel.beginPath();
 pincel.arc(300, 200, 100, 0, 2 * 3.14);
 pincel.fill();


</script>
