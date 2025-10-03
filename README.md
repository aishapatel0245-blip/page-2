# page-2
<header>
    <h1 class="color1">Logos</h1>
    <h2 class="color2 italic">Management Team</h2>
</header>

<section>
    <div class="team-member">
        <img src="ceo.jpg" alt="CEO Picture"> <!-- Picture -->
        <h3 class="bold underline">Jane Smith - CEO</h3>
        <p class="font1">Jane founded <span class="italic">Logos</span> in 2010 and oversees all company operations. Her leadership has led to significant growth in book publishing services.</p>
        <ul>
            <li>Oversees business strategy</li>
            <li>Manages executive team</li>
            <li>Leads publishing innovation</li>
        </ul>
    </div>

    <div class="team-member">
        <img src="cto.jpg" alt="CTO Picture">
        <h3 class="bold">John Doe - CTO</h3>
        <p class="font2 serif">John leads the technology and digital publishing efforts. He ensures Logos stays ahead in digital book distribution.</p>
        <ol>
            <li>Oversees IT infrastructure</li>
            <li>Develops digital tools</li>
            <li>Implements data analytics for sales</li>
        </ol>
    </div>

    <div class="team-member">
        <img src="editor.jpg" alt="Editor Picture">
        <h3 class="underline">Emily Johnson - Chief Editor</h3>
        <p class="font1">Emily manages editorial quality and guides authors through the publication process. She has a keen eye for talent.</p>
        <p>Learn more about our services <a href="https://www.example.com" target="_blank">here</a>.</p> <!-- Outside link -->
        <p>Email us: <a href="mailto:contact@logos.com">contact@logos.com</a></p> <!-- Email link -->
    </div>

    <div class="team-member">
        <p class="color1 font2 serif">Download our <a href="Logos_Company_Brochure.pdf" download>Company Brochure</a></p> <!-- Downloadable file -->
    </div>

    <div class="team-member">
        <p class="color2">Connect with us on <a href="#">LinkedIn</a> or <a href="#">Twitter</a></p> <!-- Internal links -->
    </div>
</section>

<footer>
    <p>Last Modified: <span id="date"></span></p> <!-- Auto date -->
</footer>

<script>
    // Auto update last modified date
    document.getElementById("date").textContent = new Date().toLocaleDateString();
</script>
