<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />
    <link rel="stylesheet" href="./style.css" />

    <title>Frontend Mentor | Order summary card</title>

    <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
    <style>
      .attribution {
        font-size: 11px;
        text-align: center;
      }
      .attribution a {
        color: hsl(228, 45%, 44%);
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="img">
        <img src="./images/illustration-hero.svg" alt="hero-img" />
      </div>
      <div class="content">
        <h3>Order Summary</h3>

        <p>
          You can now listen to millions of songs, audiobooks, and podcasts on
          any device anywhere you like!
        </p>

        <div class="price">
          <div class="plan">
            <img src="./images/icon-music.svg" alt="music-icon" />
            <p>
              Annual Plan <br />
              <span>$59.99/year</span>
            </p>
          </div>

          <a href="#">Change</a>
        </div>

        <a href="#" class="payment-btn">Proceed to Payment</a>
        <a href="#" class="cancel-btn">Cancel Order</a>
      </div>
    </div>

    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Anurag</a>.
    </div>
  </body>
</html>
