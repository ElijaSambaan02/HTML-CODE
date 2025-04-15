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
