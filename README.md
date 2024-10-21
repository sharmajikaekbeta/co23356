#practical 2 code :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>4 On-Campus Beverages You Should Be Drinking</title>
</head>
<body>
    <header>
        <div class="header-container">
            <img src="C:\Users\todhr\OneDrive\Desktop\New folder\WhatsApp Image 2024-07-25 at 20.59.10_9f8310e2.jpg" alt="Header Image" class="header-image">
            <div class="header-text">
                <h1>CCET(DG): 4 On-Campus Beverages You Should Be Drinking</h1>
            </div>
        </div>
    </header>
    <section class="profile">
        <img src="C:\Users\todhr\OneDrive\Desktop\New folder\WhatsApp Image 2024-07-25 at 20.59.09_bb41f2b1.jpg" alt="Profile Picture">
        <div class="profile-text">
            <p><strong>SanskarSharma</strong></p>
            <p><em>Last updated July 27, 2024</em></p>
            <hr>
        </div>
    </section>
    <section class="content">
        <article>
            <h2><span>1.</span> Italian soda at Bytes</h2>
            <p><a href="http://example.com/location-bytes">Near Block A, CCET(DG), Sector 26</a></p>
            <p>When's the last time you've had an Italian soda? It had been a while for me, but I wanted to join my friend for a non-caffeinated beverage at Bytes and I became reacquainted with the combination of fizzy water and artificial fruit syrup. Italian sodas are not so sweet as a normal soda and not so boring as a flavored carbonated water. The Italian sodas at Bytes also have no cream in them (or maybe they do if you ask; I haven't tried), which makes it a nice coffee shop alternative for the times when you're feeling a refreshing drink that doesn't have caffeine or milk.</p>
            <p class="recommendation">Recommendation: Raspberry Italian soda</p>
            <img src="C:\Users\todhr\OneDrive\Desktop\New folder\WhatsApp Image 2024-07-25 at 20.59.08_5290b491.jpg" alt="Italian Soda">
        </article>
        <article>
            <h2><span>2.</span> Bubble tea at Pop Tea Bar</h2>
            <p><a href="http://example.com/location-pop-tea-bar">Near Block A, CCET(DG), Sector 26</a></p>
            <p>Nubz is a cafe/bar newly opened in sector 26. The interiors are done well with a mixture of modern age designing with classic old school comfort. The place is divided into three areas basically which is the indoor lounge, the outdoor and rooftop seating. The inner seating area is shady and gives a classic tone to the restaurant whereas the outdoor seating is comparatively more modern with Graffiti's and funky wall frames. An ideal place to chill and relax.</p>
            <p>Coming to the food I got a chance to try a wide spread from the menu: Veg starters, Tandoori momos, Crispy shiitake mushrooms, Paneer tikka kaali Mirch, Wok tossed veggies, Cheese garlic bread, Veg galouti kebab.</p>
            <p class="recommendation">Recommendation: Classic Milk Tea with tapioca + an order of popcorn chicken.</p>
            <img src="C:\Users\todhr\OneDrive\Desktop\New folder\WhatsApp Image 2024-07-25 at 20.59.08_51eed87e.jpg" alt="Bubble Tea">
        </article>
        <article>
            <h2><span>3.</span> Latte at CoHo</h2>
            <p><a href="http://example.com/location-coho">Near Block A, CCET(DG), Sector 26</a></p>
            <p>I can't tell you whether CoHo has a particularly amazing Vanilla Bean Latte, only because CoHo is the only place I've ever ordered a Vanilla Bean Latte from. I'm not even totally sure I know what a Vanilla Bean Latte is supposed to taste like. What I do know is the Vanilla Bean Latte I ordered on a whim from CoHo was delicious.</p>
            <p class="recommendation">Recommendation: Vanilla Bean Latte</p>
            <img src="C:\Users\todhr\OneDrive\Desktop\New folder\WhatsApp Image 2024-07-25 at 20.59.08_d5be9ecb.jpg" alt="Latte at CoHo">
        </article>
        <article>
            <h2><span>4.</span> Agua Fresca at Nexus Cafe</h2>
            <p><a href="http://example.com/location-nexus-cafe">Near Block A, CCET(DG), Sector 26</a></p>
            <p>Nexus Cafe has a lot of tasty things packed into its cafeteria space, including agua fresca! Grab a cup of this fresh and fruity beverage before you head to the checkout line. Nexus Cafe has plenty of indoor and outdoor seating, too, so on the next sunny day, take a break on the patio with a cup of agua fresca, and maybe a burrito.</p>
            <p class="recommendation">Recommendation: Agua Fresca</p>
            <img src="C:\Users\todhr\OneDrive\Desktop\New folder\WhatsApp Image 2024-07-25 at 20.59.08_9481dd84.jpg" alt="Agua Fresca at Nexus Cafe">
        </article>
    </section>
</body>
</html>
































body {
    font-family: 'Source Sans Pro', sans-serif;
    margin: 0;
    padding: 0;
    color: rgb(51, 51, 51);
    line-height: 32px;
}


header {
    width: 100%;
    height: 500px;
    overflow: hidden;
    background-image: linear-gradient(rgba(0, 0, 0, .3), rgba(0, 0, 0, .3)), url(../images/header.jpg);
    background-size: cover;
    background-position: top;
}


.header-container {
    position: relative;
    width: 100%;
    height: 100%;
    text-align: center;
    color: white;
}


.header-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    max-width: 1000px;
    text-align: center;
    color: #fff;
    font-family: 'Roboto Slab', serif;
    font-size: 36px;
    font-weight: normal;
}


.header-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
}


header h1 {
    margin: 0;
    font-size: 36px;
    font-weight: normal;
    color: #fff;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}


.profile {
    position: absolute;
    top: 450px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    z-index: 1;
}


.profile img {
    border-radius: 50%;
    width: 100px;
    height: 100px;
    border: 1px solid #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}


.profile-text {
    font-family: 'Source Sans Pro', sans-serif;
    font-size: 18px;
    color: rgb(51, 51, 51);
    text-align: center;
    margin-top: 10px;
    line-height: 24px;
}


.profile-text strong {
    font-weight: bold;
}


.profile-text em {
    font-style: italic;
}


.profile-text hr {
    margin-top: 10px;
    border: none;
    height: 2px;
    background-color: #e6e6e6;
}


.content {
    width: 66.67vw;
    margin: 60px auto 0;
}


.content article {
    background: white;
    padding: 20px;
    margin-top: 170px;
    margin-bottom: 20px;
}


.content article h2 {
    margin-top: 0;
    margin-bottom: 0;
    font-family: 'Roboto Slab', serif;
    font-size: 36px;
    font-weight: bold;
    display: flex;
    align-items: center;
    color: rgb(51, 51, 51);
}


.content article h2 span {
    color: rgba(0, 0, 0, 0.25);
    margin-right: 10px;
}


.content article p {
    margin-top: 0;
    margin-bottom: 20px;
    font-family: 'Source Sans Pro', sans-serif;
    font-size: 18px;
    line-height: 32px;
}


.content img {
    width: 100%;
    height: auto;
    margin-top: 20px;
    margin-bottom: 120px;
}


.recommendation {
    font-weight: bold;
    color: #000000;
    margin-top: 20px;
    margin-bottom: 20px;
}


a {
    color: #42b4d6;
    text-decoration: none;
}


a:hover {
    text-decoration: underline;
}

