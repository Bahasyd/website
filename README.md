<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="styles.css">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Edu+AU+VIC+WA+NT+Pre:wght@400..700&family=Monsieur+La+Doulaise&display=swap" rel="stylesheet">
</head>
    <body>
        
        <div id="hero">
            <h1 id="title">Visit Bishkek <span class="underline"> capital city</span>
            </h1>
            <input class="search-input" type="text" />
            <h2> Kyrgyzstan</h2>
        </div>
        <div>
            <h3>Top three activities to do at Bishkek</h3>  
        </div>
        <section>
        <div class="activities-grid">
            <div class="activity">
                <a href="https://www.visitkyrgyz.com/places-to-go/central-mosque">
                <img src="https://www.paradigmairportservices.com/wp-content/uploads/2020/08/Bishkek_1617185458-scaled.jpg" alt="Central Mosque in Bishkek" class="img-hover">
                </a>
                <h4>Central Mosque in Bishkek</h4>
                <p>he Bishkek Central Mosque, the one of largest in Central Asia. Its area is more than 4,000 square meters. Construction of the mosque lasted six years and cost $ 25 million, it was opened in 2018.</p>
            </div>
            <div class="activity">
                <a href="https://en.wikipedia.org/wiki/Victory_Square,_Bishkek">
                    <img src="https://www.triptokyrgyzstan.com/sites/default/files/media/image/c_ahmed_d_victory_square_0.jpg" alt="Old Square Victory" class="img-hover">
                </a>
                <h4>Old Square Victory</h4>
                <p>Victory Square is a public square in the city of Bishkek dedicated to the memory of soldiers who died during the Second World War.</p>
            </div>
            <div class="activity">
                <a href="https://www.wildfrontierstravel.com/en_GB/destination/kyrgyzstan?infinity=ict2~net~gaw~cmp~520261473~ag~1323814347242490~ar~~kw~kyrgyzstan%20tours~mt~p~acr~7649413162&msclkid=5674162378de1038ead4711eaea36551&utm_source=bing&utm_medium=cpc&utm_campaign=ppc-grouped_destination-uk-central_asia&utm_term=kyrgyzstan%20tours&utm_content=ppc-grouped_destination-uk-central_asia-kyrgyzstan">
                    <img src="https://kalpak-travel.com/wp-content/uploads/2017/04/kyrgyzstan.jpg" alt="Treveling in kyrgyzstan" class="img-hover">
                </a>
                <h4>Treveling in kyrgyzstan</h4>
                <p>Kyrgystan is a mountainous country located in Central Asia. The stunning Tien Shan mountain range makes up 80% of the nation, and its verdant valleys and crystal-clear alpine lakes, serve as the country's defining features.</p>
            </div>
        </div>
    </section>

    <section class="guide">
        <a href="https://www.linkedin.com/in/bakytbek-sydykov-0295b2279/">
        <img src="https://scontent.flhr11-1.fna.fbcdn.net/v/t1.6435-9/155184010_1350865405296184_6989484158372857850_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=85N9pYH8rdEQ7kNvgHcKyzM&_nc_zt=23&_nc_ht=scontent.flhr11-1.fna&_nc_gid=Ab_Ge_Z5cNazWtUy48rQtuw&oh=00_AYCyi1QArOp2cao8WAlRC5YnYzJzd0BXQPXgUE9zZsMZCA&oe=67604993" alt="Guide photo"
        class="guite-hover">
    </a>
        <div class="guide-text">
            <p>“I have lived at Bishkek for over 20 years, so I can show you all of its best parts and hidden secrets.”</p>
            <p class="guide-name">Bakytbek Sydykov</p>
        </div>
    </section>
</body>
</html>

styles.css

body {
    text-align:center;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: linear-gradient(white,hsl(191, 22%, 41%));
}
#hero {
   background-image: url("https://media.giphy.com/media/2dhG1abbpamBi/giphy.gif");
    background-size: cover;
    padding: 400px 0 50px 0;
}

#title { 
    font-size: 100px;
    font-family: "Monsieur La Doulaise", serif;
    font-weight: absolute;
    font-style: bold;
    margin-top: 5px;
    text-shadow: 0px 0px 21px white
}
.btn { 
    padding: 6px 12px;
    background: white;
    border: none;
    font-family: "Monsieur La Doulaise", cursive;
    color: #828282;
    font-weight: 1000;
}
.underline { 
    border-bottom: 4px solid white;
}
.monsieur-la-doulaise-regular {
    font-family: "Monsieur La Doulaise", serif;
    font-weight: 400;
    font-style: normal;
  }
  .search-input {
    display: block;
    width: 400px;
    margin-left: auto;
    margin-right: auto;
    line-height: 24px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 30px;
    padding-right: 30px;
    border: 1px solid #dfe1e5;
    border-radius: 24px;
}

img {
    width: 100px;
}

.hero-text h1 {
    font-size: 2em;
    margin-bottom: 0.5em;
}

.activities-grid {
    text-align: center;
    padding: 2em 0;
    font-size: 1em;
    margin-bottom: 1em;
    margin-top: 1em;
    display: flex;
    justify-content: center;
    gap: 4em;
   
}

.activity {
    max-width: 200px;
    text-align: center;
}

.activity img {
    width: 100%;
    border-radius: 100%;
}

.guide {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 2em;
    background-image: url(https://cdn.getyourguide.com/img/tour/fa86e4dcd1033413e2b58ebd027003d7717d320f05e99f7eb779a08f03ae1ffc.jpg/145.jpg);
}

.guide img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-right: 1em;
}
.guite-hover{
    transition:  0.5s;
}
.guite-hover:hover{
    width: 120px;
}
.guide-text {
    max-width: 300px;
    text-align: left;
}

.guide-name {
    font-weight: bold;
    margin-top: 0.5em;
}

.img-hover{
    transition: all ease-in-out 0.5s;
}
.img-hover:hover{
    width: 250px;
}
