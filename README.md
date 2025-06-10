# rome-foodie-tour
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rome Foodie Tour</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Fredoka One', cursive;
      background: #fff8f0;
      color: #333;
    }
    header {
      background: #9b2226;
      padding: 4rem 1rem 2rem;
      text-align: center;
      color: #fff;
      position: relative;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
      text-shadow: 2px 2px #00000055;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }
    nav {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
  justify-items: center;
  gap: 1rem;
  background: #fff;
  padding: 1rem;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  position: sticky;
  top: 0;
  z-index: 10;
}
    nav a {
      text-decoration: none;
      color: #9b2226;
      font-weight: bold;
      font-size: 1rem;
    }
    .section-box {
  background: #ffffff;
  border-radius: 1.5rem;
  box-shadow: 4px 4px 16px rgba(0, 0, 0, 0.1);
  padding: 2rem;
  margin: 2rem auto;
  max-width: 1000px;
  transition: transform 0.3s ease-in-out;
}
.section-box:hover {
  transform: scale(1.01);
}
    .section-box h2 {
      color: #9b2226;
      margin-top: 0;
    }
    .illustration {
      text-align: center;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
      margin-bottom: 2rem;
    }
    .illustration img {
      max-width: 100px;
    }
    .gallery-slideshow {
  display: flex;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  gap: 1rem;
  padding: 1rem 0;
  border-top: 2px dashed #f4a261;
  border-bottom: 2px dashed #f4a261;
}
    .gallery-slideshow img {
      width: 100%;
      max-width: 600px;
      border-radius: 1rem;
      scroll-snap-align: center;
      flex: 0 0 auto;
    }
    .review-carousel {
      display: flex;
      overflow-x: auto;
      gap: 1rem;
      scroll-snap-type: x mandatory;
      padding-bottom: 1rem;
    }
    .review {
      min-width: 300px;
      flex: 0 0 auto;
      scroll-snap-align: start;
      background: #fef6e4;
      padding: 1rem;
      border-left: 5px solid #52796f;
      border-radius: 0.75rem;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    input, textarea {
      padding: 1rem;
      border-radius: 0.75rem;
      border: 2px solid #ccc;
      font-family: 'Fredoka One', cursive;
    }
    button {
      padding: 1rem;
      background-color: #52796f;
      color: white;
      border: none;
      border-radius: 1rem;
      font-weight: bold;
      font-size: 1.1rem;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #ffeadb;
      color: #555;
    }
    .chef-photo {
      width: 200px;
      height: auto;
      border-radius: 1rem;
      object-fit: cover;
      border: 4px solid #52796f;
      margin: 1rem auto;
      display: block;
    }
  </style>
</head>
<body>
  <header style="background: linear-gradient(135deg, #9b2226 40%, #e63946 100%); padding: 5rem 1rem 3rem; text-align: center; color: #fff; position: relative;">
  <h1 style="font-size: 3.5rem; margin: 0; text-shadow: 3px 3px #00000033; letter-spacing: 1px; display: flex; justify-content: center; align-items: center; gap: 1rem;">
    <img src="https://cdn-icons-png.flaticon.com/512/3595/3595455.png" alt="Pizza Logo" style="height: 60px; vertical-align: middle;"> Rome Foodie Tour 🇮🇹
  </h1>
  <p style="font-size: 1.4rem; margin-top: 1rem; font-style: italic;">
    An unforgettable food adventure with Ludovica in the heart of Rome
  </p>
  <div style="font-size: 2rem; margin-top: 1rem;">
  🍷 🧀 🍕 🌿 🍅 🥖 🍨
</div>
<a href="#contact" style="margin-top: 1rem; display: inline-block; background: #f4a261; color: white; font-weight: bold; padding: 0.8rem 1.5rem; border-radius: 2rem; text-decoration: none; font-size: 1.2rem; box-shadow: 2px 2px 6px rgba(0,0,0,0.2);">Book Now</a>
</header>
  <nav>
    <a href="#about">About</a>
    <a href="#tour">Tour</a>
    <a href="#gallery">Gallery</a>
    <a href="#reviews">Reviews</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="illustration">
  <span style="font-size: 2.5rem">🍅</span>
  <span style="font-size: 2.5rem">👨‍🍳</span>
  <span style="font-size: 2.5rem">🍝</span>
  <span style="font-size: 2.5rem">🌿</span>
  <span style="font-size: 2.5rem">🥄</span>
</div>

  <section id="about" class="section-box">
    <h2>Meet Ludovica</h2>
    <img class="chef-photo" src="https://example.com/images/IMG_2222.jpeg" alt="Ludovica smiling">
    <p>Ciao! I'm Ludovica, Sicilian by blood and Roman by heart. I've lived in Rome for over 10 years and spent every summer cooking aboard luxury catamarans and yachts. But my culinary journey started much earlier—rooted in the warm kitchens of my childhood, where my <strong>nonna</strong> and <strong>mamma</strong> passed down not just recipes, but rituals of love, patience, and joy. Every dish I serve carries their legacy, every flavor a memory of Sunday lunches and fresh basil on the windowsill. Now I welcome you to experience this tradition in the streets of Rome and Trastevere, through a food tour that blends my heritage with the vibrant energy of the Eternal City.</p>
  </section>

  <section id="tour" class="section-box">
    <h2>What You'll Taste</h2>
    <ul>
      <li>🍕 Pizza, Pasta, Porchetta, Supplì, Salumi, Bruschetta</li>
      <li>🫒 Traditional Balsamic Vinegar from Modena</li>
      <li>🧀 Mozzarella di Bufala & Parmigiano Reggiano</li>
      <li>🍷 DOCG Italian wines & exclusive tastings</li>
            <li>🍨 Real Italian Gelato — and much more!</li>
    </ul>
  </section>

  <section id="highlights" class="section-box">
  <h2>Why You'll Love This Tour</h2>
  <p style="margin-bottom: 1rem; font-size: 1.1rem; line-height: 1.6;">Picture yourself wandering through Rome's charming streets with a glass of DOCG wine in hand, nibbling on delicious bites and laughing with new foodie friends. Each tasting comes with a fun story — maybe a quiet alley where Roman nobility once dined, or Ludovica’s childhood memories of Sicilian Sunday feasts. This isn’t a tour. It’s a journey through flavor, culture, and the warmth of Italian hospitality.</p>
  <ul style="list-style: none; padding: 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem;">
    <li style="background: #fff4e6; padding: 1.2rem; border-radius: 1rem; box-shadow: 2px 2px 10px rgba(0,0,0,0.05);">💬 Small, intimate groups for a personal experience</li>
    <li style="background: #e0f7f1; padding: 1.2rem; border-radius: 1rem; box-shadow: 2px 2px 10px rgba(0,0,0,0.05);">🍷 DOCG wines paired with authentic bites</li>
    <li style="background: #fef6e4; padding: 1.2rem; border-radius: 1rem; box-shadow: 2px 2px 10px rgba(0,0,0,0.05);">👣 Explore hidden gems in Trastevere & historic Rome</li>
    <li style="background: #f1e0f7; padding: 1.2rem; border-radius: 1rem; box-shadow: 2px 2px 10px rgba(0,0,0,0.05);">🧑‍🍳 Hosted by a real Italian chef with Sicilian soul</li>
  </ul>
</section>

<section class="section-box" style="background: #fff0f5;">
  <h2>What's Included</h2>
  <ul style="padding-left: 1.2rem; line-height: 1.8;">
    <li>✔️ 4 hand-picked tasting locations</li>
    <li>✔️ 50+ tastings of savory and sweet delights</li>
    <li>✔️ DOCG wine pairings and a visit to a local winery</li>
    <li>✔️ Local guide, fluent in food and folklore</li>
  </ul>
</section>


    <p style="margin-bottom: 1rem; font-size: 1.05rem; line-height: 1.6;">
      Perfect for private groups, couples, or families looking for a unique experience. The tour requires a minimum of 2 people and is limited to a maximum of 14 guests to keep the vibe intimate and exclusive. Pricing varies depending on group size.
    </p>
    <ul style="padding-left: 1.2rem; line-height: 1.8;">
    <li>🍝 Curious foodies looking for authentic Roman flavors</li>
    <li>👨‍👩‍👧 Families and couples — solo travelers welcome when booking for two</li>
    <li>📸 Travelers who want delicious memories and great photos</li>
    <li>🥂 Anyone who enjoys good food, good wine, and better stories</li>
  </ul>
</section>

  <section id="gallery" class="section-box">
    <h2>Gallery</h2>
    <div class="gallery-slideshow">
  <img src="https://example.com/images/IMG_2222.jpeg" alt="Pasta with pesto" />
  <img src="https://example.com/images/IMG_2221.jpeg" alt="Carbonara" />
  <img src="https://example.com/images/IMG_2207.jpeg" alt="Cheese Plate" />
  <img src="https://example.com/images/IMG_1463_2.jpeg" alt="Food Tour Group 2" />
  <img src="https://example.com/images/IMG_1614.jpeg" alt="Food Tour Group 3" />
  <img src="https://example.com/images/Food-Tour-with-Pablo-106-scaled.jpeg" alt="Cheese with animals" />
  <img src="https://example.com/images/Food-Tour-with-Pablo-86-scaled.jpeg" alt="Aperitivo Toast" />
  <img src="https://example.com/images/Food-Tour-with-Pablo-98-scaled.jpeg" alt="Salumi Shop" />
</div>
  </section>

  <section id="reviews" class="section-box">
    <h2>Reviews</h2>
    <div class="review-carousel">
  <div class="review"><p>I didn’t think I could love food more until Lu’s tour. Every bite was incredible and the stories made it even richer!</p></div>
  <div class="review"><p>Absolutely unforgettable. The porchetta stop made my trip. Ludovica is a gem!</p></div>
  <div class="review"><p>My friends and I are still talking about the pasta we had. Thank you Lu for such a fun and tasty experience!</p></div>
  <div class="review"><p>Lu is an absolute treat of a guide! We loved every stop in the tour and she was well informed and full of great information. Would recommend to anyone!</p></div>
  <div class="review"><p>LU was the BEST! Our family of 11 had the best time and she was the most knowledgeable and shared countless stories and facts about the food we ate. She made sure our experience was memorable and was so very patient! One of the best tours of our trip so far!</p></div>
  <div class="review"><p>Lu was an amazing guide!! The wine was free flowing, the food was amazing and the hospitality was top notch. I would highly recommend this tour to anyone who eats food!</p></div>
  <div class="review"><p>Great day, Lu was fantastic, very informative and helpful. The food was tasty!</p></div>
  <div class="review"><p>Ludovica has a deep understanding and passion for food that excited the curiosity of the food introduced. She has a warm congeniality that was well appreciated. Thank you again!</p></div>
  <div class="review"><p>Lu’s food tour has been one of the best things we have done in Rome so far. She made us feel like locals and gave us several unique experiences with delicious food and wine.</p></div>
  <div class="review"><p>Lu was the best. So knowledgeable and made sure we had a great time while we ate incredible food. Would definitely recommend.</p></div>
  <div class="review"><p>10/10 recommend! Lu was great and incredibly knowledgeable. The food was great and she was a phenomenal host. Definitely come hungry, lots of food and wine!</p></div>
  <div class="review"><p>Excellent tour of 4 local restaurants. Great food, wine and camaraderie. Our tour guide, Lu, couldn’t have been more knowledgeable or fun. Would highly recommend this tour!</p></div>
</div>
  </section>

  <section id="calendar" class="section-box">
    <a href="#contact" style="float: right; margin-bottom: 1rem; background: #9b2226; color: white; font-weight: bold; padding: 0.6rem 1.2rem; border-radius: 2rem; text-decoration: none; font-size: 1rem;">Book Now</a>
    <h2>Availability Calendar</h2>
    <p><strong>Pick a date and join us in the heart of Rome!</strong></p>
    <iframe src="https://calendar.google.com/calendar/embed?src=en.italian%23holiday%40group.v.calendar.google.com&ctz=Europe%2FRome" style="border: 0" width="100%" height="400" frameborder="0" scrolling="no"></iframe>
  </section>

  <section id="contact" class="section-box">
    <h2>Contact & Booking</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Message or Booking Request" rows="5"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Flavors of Roma. Taste. Connect. Discover.</p>
  </footer>
</body>
</html>
