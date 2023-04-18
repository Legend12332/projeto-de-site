# Aló
<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js"></script>

<section class="pyscript">
   Hello world! <br>
     This is the current date and time, as computed by Python:
     <py-script>
     from datetime import datetime
     now = datetime.now()
     display(now.strftime("%m/%d/%Y, %H:%M:%S"))
     print("hello camarada")
     </py-script>
</section>


<button name="button">Click me</button>