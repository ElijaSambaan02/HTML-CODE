<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sinulog Festival 2025</title>
  <link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Fjalla+One&family=Poppins:wght@600&display=swap" rel="stylesheet"/>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background: url('https://cdn.techinasia.com/wp-content/uploads/2014/01/Sinulog-720x358.png') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }

    header {
      background-color: rgba(248, 85, 37, 0.9);
      padding: 10px 0;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }

    header h1 {
      font-family: 'Archivo Black', sans-serif;
      font-size: 2rem;
      margin: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-size: 1rem;
    }

    .container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background-color: rgba(0, 0, 0, 0.7);
      margin: 90px 20px 20px;
      padding: 20px;
      border-radius: 10px;
    }

    .text {
      width: 50%;
      text-align: left;
      padding: 20px;
    }

    .image {
      width: 50%;
    }

    .image img {
      width: 100%;
      border-radius: 10px;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #F85525;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
      cursor: pointer;
      border: none;
      font-size: 1rem;
    }

    .btn:hover {
      background-color: #d94a1f;
    }

    footer {
      background-color: rgba(51, 51, 51, 0.8);
      color: white;
      padding: 10px;
      width: 100%;
    }

    h2 {
      background-color: #F85525;
      padding: 10px;
      border-radius: 5px;
      display: inline-block;
      font-family: 'Fjalla One', sans-serif;
      color: black;
    }

    .modal {
      display: none;
      position: fixed;
      z-index: 2000;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      justify-content: center;
      align-items: center;
    }

    .modal-content {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      width: 80%;
      max-width: 500px;
      color: black;
      position: relative;
    }

    .close {
      color: red;
      font-size: 24px;
      font-weight: bold;
      position: absolute;
      right: 15px;
      top: 10px;
      cursor: pointer;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }

      .text, .image {
        width: 100%;
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>SINULOG FESTIVAL 2025</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#schedule">Event Schedule</a>
      <a href="#tickets">Get Tickets</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- ABOUT -->
  <section id="about" class="container">
    <div class="text">
      <h2>ABOUT THE SINULOG FESTIVAL</h2>
      <p>Sinulog Festival is a big and colorful event in Cebu, Philippines. It happens every January to honor Santo Niño, the child Jesus. People wear bright costumes and dance in the streets. The dance moves follow a special beat, like waves in the ocean. There are big parades with music, drums, and happy people. Many tourists visit Cebu to see the festival and take pictures.</p>
      <button class="btn" onclick="window.location.href='about.html'">Click More</button>
    </div>
    <div class="image">
      <img src="https://media.assettype.com/tribune%2F2024-01%2F0cb7e09d-1358-4556-b312-c69dd53d99b1%2Fviber_image_2024_01_19_22_21_52_042.jpg" alt="Sinulog Festival"/>
    </div>
  </section>

  <!-- SCHEDULE -->
  <section id="schedule" class="container">
    <div class="text">
      <h2>EVENT SCHEDULE</h2>
      <ul>
        <li style="cursor: pointer;" onclick="openEventDetails('event1')"><strong>January 13:</strong> Festival Queen Runway Competition</li>
        <li style="cursor: pointer;" onclick="openEventDetails('event2')"><strong>January 16:</strong> Cultural Show by CITU & USFP</li>
        <li style="cursor: pointer;" onclick="openEventDetails('event3')"><strong>January 17:</strong> Sinulog Grand Opening & Street Party</li>
        <li style="cursor: pointer;" onclick="openEventDetails('event4')"><strong>January 18:</strong> Fluvial Parade & Religious Procession</li>
        <li style="cursor: pointer;" onclick="openEventDetails('event5')"><strong>January 19:</strong> Sinulog Grand Parade & Fireworks</li>
      </ul>
    </div>
  </section>

  <!-- TICKETS -->
  <section id="tickets" class="container">
    <div class="text">
      <h2>GET YOUR TICKETS</h2>
      <ul>
        <li><strong>🎟️ VIP:</strong> ₱5,000 - Front row, free drinks, after-party access</li>
        <li><strong>🎟️ Gen. Green:</strong> ₱1,500 - Great parade view</li>
        <li><strong>🎟️ Gen. Yellow:</strong> ₱1,000 - Standard view</li>
      </ul>
      <button class="btn" onclick="openModal('ticketModal')">BUY TICKETS NOW!</button>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="container">
    <div class="text">
      <h2>CONTACT US</h2>
      <p>Contact / Get Involved
        Want to sponsor, perform, or volunteer?</p>
      <p> 📧 Email us at sinulogfest@gmail.com</p>
      <p>📱 Follow us</p>
      <p>Instagram: @sinulogfest</p>
      <p>TikTok: @sinulogfest </p>
      <p>Facebook: Sinulog Festival</p>
      <p>Twitter: @sinulogfes</p>
    </div>
  </section>

  <!-- FEEDBACK -->
  <section class="container">
    <div class="text">
      <h2>FEEDBACK</h2>
      <p>You can share your feedback, comments, or questions here:</p>
      <form id="feedbackForm">
        <label for="userFeedback">Your Feedback:</label><br/>
        <textarea id="userFeedback" rows="4" style="width: 100%; border-radius: 5px; padding: 10px;" required></textarea><br/><br/>
        <button class="btn" type="submit">Submit Feedback</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Sinulog Festival. Viva Pit Señor!</p>
  </footer>

  <!-- Event Details Modal -->
  <div id="eventModal" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('eventModal')">&times;</span>
      <h2 id="eventTitle">Event Details</h2>
      <p id="eventDetails"></p>
    </div>
  </div>

  <!-- Ticket Modal -->
  <div id="ticketModal" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('ticketModal')">&times;</span>
      <h2>Fill Your Information</h2>
      <form id="ticketForm">
        <label for="name">Name:</label>
        <input type="text" id="name" required/><br/><br/>
        <label for="phone">Phone Number:</label>
        <input type="text" id="phone" required/><br/><br/>
        <label for="email">Email Address:</label>
        <input type="email" id="email" required/><br/><br/>
        <label for="address">Home Address:</label>
        <input type="text" id="address" required/><br/><br/>
        <label for="ticketType">Choose Ticket:</label>
        <select id="ticketType">
          <option value="VIP">VIP - ₱5,000</option>
          <option value="Gen. Green">Gen. Green - ₱1,500</option>
          <option value="Gen. Yellow">Gen. Yellow - ₱1,000</option>
        </select><br/><br/>
        <button class="btn" type="submit">Proceed to Payment</button>
      </form>
    </div>
  </div>

  <script>
    function openModal(id) {
      document.getElementById(id).style.display = 'flex';
    }

    function closeModal(id) {
      document.getElementById(id).style.display = 'none';
    }

    function openEventDetails(eventId) {
      const eventDetails = {
        'event1': { title: 'Festival Queen Runway Competition', details: 'This is the grand opening event with vibrant costumes and a runway show.' },
        'event2': { title: 'Cultural Show by CITU & USFP', details: 'A celebration of Filipino culture with music and dance performances.' },
        'event3': { title: 'Sinulog Grand Opening & Street Party', details: 'Join the street party with parades, dancers, and music.' },
        'event4': { title: 'Fluvial Parade & Religious Procession', details: 'A solemn procession to honor Santo Niño on the waters of Cebu.' },
        'event5': { title: 'Sinulog Grand Parade & Fireworks', details: 'The grand finale with a massive parade and stunning fireworks display.' }
      };

      const event = eventDetails[eventId];
      document.getElementById('eventTitle').textContent = event.title;
      document.getElementById('eventDetails').textContent = event.details;

      openModal('eventModal');
    }

    document.getElementById("ticketForm").addEventListener("submit", function(event) {
      event.preventDefault();
      alert("Thank you! Your ticket has been successfully purchased.");
      closeModal('ticketModal');
    });

    document.getElementById("feedbackForm").addEventListener("submit", function(event) {
      event.preventDefault();
      const feedback = document.getElementById("userFeedback").value;
      if (feedback.trim() !== "") {
        alert("Thank you for your feedback!");
        document.getElementById("userFeedback").value = "";
      }
    });
  </script>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sinulog Festival - About</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet"/>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      background-color: #F85525;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }

    section#about {
      padding: 40px 20px;
      text-align: center;
    }

    section#about h2 {
      font-size: 2rem;
      color: #F85525;
      margin-bottom: 20px;
    }

    section#about img {
      width: 80%;
      max-width: 600px;
      border-radius: 10px;
      margin-top: 20px;
    }

    section#about p {
      font-size: 1rem;
      margin: 20px 0;
      line-height: 1.6;
      color: #444;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 30px;
    }

  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <h1>Sinulog Festival 2025</h1>
  </header>

  <!-- ABOUT SECTION -->
  <section id="about">
    <h2>About the Sinulog Festival</h2>

    <img src="https://gttp.images.tshiftcdn.com/223482/x/0/cebu-cebu-city-sinulog-festival-erwinlim-20191227.jpg?ar=1.91%3A1&w=1200&fit=crop" alt="Sinulog Festival" />

    <p>The Sinulog Festival is a vibrant and grand annual cultural and religious celebration held in Cebu City, Philippines, in honor of the Santo Niño, or the Child Jesus. This festival takes place every third Sunday of January and is one of the most popular and well-attended events in the country. The Sinulog is known for its grand parade, featuring dancers in colorful costumes, and its rhythmic drumbeats that mimic the waves of the sea. The festival also showcases street parties, religious processions, food stalls, and cultural shows.</p>

    <p>During the festival, people from all over the Philippines and even tourists from abroad gather to join the celebration. The highlight of the Sinulog is the street dancing, where participants perform the traditional "Sinulog" dance — a forward and backward step that mimics the movement of water. The event also honors the conversion of the Filipino people to Christianity, making it a spiritual occasion for many as they pray to the Santo Niño for blessings and protection.</p>

    <p>The Sinulog Festival offers not only entertainment but also a chance to experience the rich history, culture, and devotion of the Filipino people. Visitors can enjoy local delicacies, view intricate parades, and witness the grand fireworks display at night.</p>
  </section>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sinulog Festival 2025 - Event Schedule</title>
  <link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Fjalla+One&family=Poppins:wght@600&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      font-weight: 600;
      margin: 0;
      padding: 0;
      text-align: center;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background-color: rgba(248, 85, 37, 0.9);
      padding: 10px 0;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }
    header h1 {
      font-family: 'Archivo Black', sans-serif;
      font-size: 2rem;
      margin: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-size: 1rem;
    }
    .container {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 90px;
      padding: 20px;
    }
    .text {
      width: 60%;
      text-align: left;
      padding: 20px;
    }
    .clickable-date {
      color: #f85525;
      cursor: pointer;
      text-decoration: underline;
    }
    .event-modal {
      display: none;
      position: fixed;
      z-index: 2000;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      justify-content: center;
      align-items: center;
    }
    .event-modal-content {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      width: 80%;
      max-width: 500px;
      color: black;
      position: relative;
    }
    .close {
      color: red;
      font-size: 24px;
      font-weight: bold;
      position: absolute;
      right: 15px;
      top: 10px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sinulog Festival 2025 - Event Schedule</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="schedule.html">Event Schedule</a>
      <a href="tickets.html">Get Tickets</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <!-- SCHEDULE -->
  <section id="schedule" class="container">
    <div class="text">
      <h2>Event Schedule</h2>
      <p>
        <span class="clickable-date" onclick="showEventDetails('event1')">January 13</span>: Festival Queen Runway Competition
      </p>
      <p>
        <span class="clickable-date" onclick="showEventDetails('event2')">January 16</span>: Cultural Show by CITU & USFP
      </p>
      <p>
        <span class="clickable-date" onclick="showEventDetails('event3')">January 17</span>: Sinulog Grand Opening & Street Party
      </p>
      <p>
        <span class="clickable-date" onclick="showEventDetails('event4')">January 18</span>: Fluvial Parade & Religious Procession
      </p>
      <p>
        <span class="clickable-date" onclick="showEventDetails('event5')">January 19</span>: Sinulog Grand Parade & Fireworks
      </p>
    </div>
  </section>

  <!-- Event Modals -->
  <div id="event1" class="event-modal">
    <div class="event-modal-content">
      <span class="close" onclick="closeEventModal('event1')">&times;</span>
      <h2>January 13 - Festival Queen Runway Competition</h2>
      <p>This event will showcase Cebu's top beauty queens, featuring a spectacular runway competition. Don't miss the glitz and glam!</p>
      <img src="https://media.assettype.com/sunstar%2Fimport%2Fuploads%2Fimages%2F2019%2F01%2F17%2F117522.jpg" alt="Event Image 1" style="width: 100%; border-radius: 10px;">
    </div>
  </div>

  <div id="event2" class="event-modal">
    <div class="event-modal-content">
      <span class="close" onclick="closeEventModal('event2')">&times;</span>
      <h2>January 16 - Cultural Show by CITU & USFP</h2>
      <p>The Cultural Show will feature performances by CITU and USFP students, showcasing Cebu's rich history and culture through music and dance.</p>
      <img src="https://cebutrip.net/files/1f19f3671acb588b701f15380b8b833e.jpg" alt="Event Image 2" style="width: 100%; border-radius: 10px;">
    </div>
  </div>

  <div id="event3" class="event-modal">
    <div class="event-modal-content">
      <span class="close" onclick="closeEventModal('event3')">&times;</span>
      <h2>January 17 - Sinulog Grand Opening & Street Party</h2>
      <p>The Grand Opening Parade will feature beautiful floats, traditional dances, and a lively street party! It's the perfect way to kick off Sinulog.</p>
      <img src="https://zee.ph/wp-content/uploads/2020/01/11426398_433975206775286_2556101862441213026_o-1024x682-1-1024x683.jpg" alt="Event Image 3" style="width: 100%; border-radius: 10px;">
    </div>
  </div>

  <div id="event4" class="event-modal">
    <div class="event-modal-content">
      <span class="close" onclick="closeEventModal('event4')">&times;</span>
      <h2>January 18 - Fluvial Parade & Religious Procession</h2>
      <p>The Fluvial Parade and the religious procession are part of the most sacred and revered traditions of the Sinulog Festival. Come and witness the devotion!</p>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKRoRQcDXxYjVpVZz8FeVCXw0MC7gnlGUgfQ&s" alt="Event Image 4" style="width: 100%; border-radius: 10px;">
    </div>
  </div>

  <div id="event5" class="event-modal">
    <div class="event-modal-content">
      <span class="close" onclick="closeEventModal('event5')">&times;</span>
      <h2>January 19 - Sinulog Grand Parade & Fireworks</h2>
      <p>The grand parade features magnificent floats, cultural performances, and the fireworks display that will light up the night sky!</p>
      <img src="https://149361529.v2.pressablecdn.com/wp-content/uploads/2019/01/Sto-Nino.jpg" alt="Event Image 5" style="width: 100%; border-radius: 10px;">
    </div>
  </div>

  <!-- JavaScript for Event Modals -->
  <script>
    // Show the event details modal when a date is clicked
    function showEventDetails(eventId) {
      document.getElementById(eventId).style.display = 'flex';
    }

    // Close the event modal when the 'X' button is clicked
    function closeEventModal(eventId) {
      document.getElementById(eventId).style.display = 'none';
    }
  </script>

</body>
</html>



tickets.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Get Tickets</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      font-weight: 600;
      margin: 0;
      padding: 0;
      text-align: center;
      background-color: #f4f4f4;
      color: black;
    }
    header {
      background-color: rgba(248, 85, 37, 0.9);
      padding: 10px 0;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }
    header h1 {
      font-family: 'Archivo Black', sans-serif;
      font-size: 2rem;
      margin: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-size: 1rem;
    }
    footer {
      background-color: rgba(51, 51, 51, 0.8);
      color: white;
      padding: 10px;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sinulog Festival 2025</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="schedule.html">Event Schedule</a>
      <a href="tickets.html">Get Tickets</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <div class="container">
    <h2>Get Your Tickets</h2>
    <p>Reserve your spot for Sinulog Festival 2025 now!</p>
    <ul style="list-style: none; padding: 0;">
      <li><strong>🎟️ VIP:</strong> ₱5,000 - Front row, free drinks, after-party access</li>
      <li><strong>🎟️ Gen. Green:</strong> ₱1,500 - Great parade view</li>
      <li><strong>🎟️ Gen. Yellow:</strong> ₱1,000 - Standard view</li>
    </ul>
  </div>

  <footer>
    <p>&copy; 2025 Sinulog Festival. Viva Pit Señor!</p>
  </footer>

</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Us</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      font-weight: 600;
      margin: 0;
      padding: 0;
      text-align: center;
      background-color: #f4f4f4;
      color: black;
    }
    header {
      background-color: rgba(248, 85, 37, 0.9);
      padding: 10px 0;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }
    header h1 {
      font-family: 'Archivo Black', sans-serif;
      font-size: 2rem;
      margin: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-size: 1rem;
    }
    footer {
      background-color: rgba(51, 51, 51, 0.8);
      color: white;
      padding: 10px;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sinulog Festival 2025</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="schedule.html">Event Schedule</a>
      <a href="tickets.html">Get Tickets</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <div class="container">
    <h2>Contact Us</h2>
    <p>If you have any questions, feel free to reach out!</p>
    <p>Email: <strong>info@sinulog2025.com</strong></p>
    <p>Phone: <strong>+63 32 123 4567</strong></p>
  </div>

  <footer>
    <p>&copy; 2025 Sinulog Festival. Viva Pit Señor!</p>
  </footer>

</body>
</html>
