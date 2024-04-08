%{
  title: "Fundraise",
  author: "Josh Chernoff",
  tags: ~w(donation fundraisers),
  description: "",
  wrapper_class: "",
}
---

<div class="relative isolate overflow-hidden py-20">
<img
    src="/assets/images/forestBanner.jpg"
    class="absolute inset-0 -z-10 object-center object-cover opacity-[.3] h-full w-full"
/>
<div class="mx-auto max-w-4xl flex flex-col h-full items-center justify-center">
  <h1 class="font-black text-base-content tracking-tight text-5xl py-0 sm:py-12 mb-4">
    Fundraisers
  </h1>
</div>
</div>

<div class="px-8 sm:px-0 prose lg:prose-lg mx-auto py-20">
<div class="">
  <div class="">
    <div class="fundraise-image-box">
      <img src="images/covid-boxes-sq.jpg" class="align-self-start mr-3" alt="Several COVID relief boxes, one open showing its contents">
    </div>
    <div class="media-body">
      <h3 class="mt-0">COVID Stress Relief Box</h3>
      <p class="mb-0">How do you relieve stress these days? We, at ACAP, had an idea to both educate our clients
        about COVID-19 health and safety guidelines and demystify the pandemic for them. The COVID Stress Relief
        Box was developed, designed, and assembled as part of a unique teaching collaboration between the ACAP
        Mentor program, ACAP core staff and our on-site partners at Community Workshop</p>
      <br>
      <p class="mb-0">
      </p><ul>
        <li>COVID STRESS RELIEF BOXES are $15 each plus $2/box for shipping.</li>
        <li>You can also coordinate with us for local pick-up at no cost!</li>
        <li>Turn-around time for orders of up to 10 boxes is up to 10 business days.</li>
        <li>For orders of more than 10 boxes, please contact us directly at acapdonate@gmail.com or call at the
          office: 503-649-2066.</li>
        <li><strong>Pick-up:</strong> After you place your order, we will contact you to arrange a time to pick
          up your item(s).</li>
      </ul>
      <p></p>

      <h4>Order Now:</h4>
      
      <form>
        <label>Select one:</label>
        <br>
        <div class="form-check form-check-inline">
          <input class="form-check-input" onclick="deliveryCheck();" type="radio" name="inlineRadioOptions" id="delivery" value="option1">
          <label class="form-check-label" for="inlineRadio1">Delivery</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" onclick="pickupCheck();" type="radio" name="inlineRadioOptions" id="pickup" value="option2">
          <label class="form-check-label" for="inlineRadio2">Pick-up</label>
        </div>
      </form>

      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" id="delivery-form">
        <input type="hidden" name="cmd" value="_s-xclick">
        <input type="hidden" name="hosted_button_id" value="YP5DJRDXRKS66">
        <table>
          <tbody><tr>
            <td>Select Quantity for Delivery:</td>
          </tr>
          <tr>
            <td><input type="number" name="quantity" value="1" min="1" max="10"></td>
          </tr>
        </tbody></table>
        <br>
        <input type="submit" class="btn btn-primary" name="submit" value="Buy Now" alt="PayPal - The safer, easier way to pay online!">
        <img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
        <br>
        <img src="images/paypal-badge.png" class="pp-badge" alt="Payments through Paypal">
      </form>

      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" id="pickup-form">
        <input type="hidden" name="cmd" value="_s-xclick">
        <input type="hidden" name="hosted_button_id" value="7TR757BCKXL2G">
        <table>
          <tbody><tr>
            <td>Select Quantity for Pick-up:</td>
          </tr>
          <tr>
            <td><input type="number" name="quantity" value="1" min="1" max="10"></td>
          </tr>
        </tbody></table>
        <br>
        <input type="submit" class="btn btn-primary" name="submit" value="Buy Now" alt="PayPal - The safer, easier way to pay online!">
        <img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
        <br>
        <img src="images/paypal-badge.png" class="pp-badge" alt="Payments through Paypal">
      </form>

    </div>
  </div>
</div>

<br>

<!-- Flock-a-Friend Fundraiser Description -->

<div class="container">
  <div class="media">
    <div class="fundraise-image-box">
      <img src="images/flamingo-sq.jpg" class="align-self-start mr-3" alt="Some plastic flamingos in a yard.">
      <p class="image-credit"><a href="https://www.flickr.com/photos/37996646802@N01/2458613657" target="_blank" title="Flamingo image source (opens in new tab)">"Flamingo Land"</a> by <a href="https://www.flickr.com/photos/37996646802@N01" target="_blank" title="cogdogblog's profile (opens in new tab)">cogdogblog</a> is licensed under <a href="https://creativecommons.org/licenses/cc0/1.0/?ref=ccsearch&amp;atype=html" target="_blank" title="CC0 1.0 description (opens in new tab)">CC0 1.0</a></p>
    </div>
    <div class="media-body">
      <h3 class="mt-0">Flock-a-Friend</h3>
      <p class="mb-0">A playful fundraiser for our campers.</p>

      <p class="mb-0">For $12.00 you can have a lawn flamingo delivered to a friend, neighbor, or family member.
        For $20.00 you can get a pair. Any additional after two is $10.00 each. Free local delivery. Outside the
        Greater Portland Metro Area there will be an extra charge for shipping and handling.</p>

      <p class="mb-0">All proceeds directly benefit the kids and young adults with autism at summer camp. If you
        have questions or would like more information, please call the office (503)649-2066.</p>

      <p class="mb-0">Call (503) 649-2066 to place your order!</p>

      <br>

      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
        <input type="hidden" name="cmd" value="_s-xclick">
        <input type="hidden" name="hosted_button_id" value="XQDV2PSFWEP8Y">
        <table>
          <tbody><tr>
            <td><input type="hidden" name="on0" value="Flamingos">Choose number of flamingos:</td>
          </tr>
          <tr>
            <td>
              <select name="os0">
                <option value="1 Flamingo">1 Flamingo $12.00 USD</option>
                <option value="2 Flamingos">2 Flamingos $20.00 USD</option>
                <option value="3 Flamingos">3 Flamingos $30.00 USD</option>
                <option value="4 Flamingos">4 Flamingos $40.00 USD</option>
                <option value="5 Flamingos">5 Flamingos $50.00 USD</option>
                <option value="6 Flamingos">6 Flamingos $60.00 USD</option>
                <option value="7 Flamingos">7 Flamingos $70.00 USD</option>
                <option value="8 Flamingos">8 Flamingos $80.00 USD</option>
                <option value="9 Flamingos">9 Flamingos $90.00 USD</option>
                <option value="10 Flamingos">10 Flamingos $100.00 USD</option>
              </select>
            </td>
          </tr>
        </tbody></table>
        <br>
        <input type="hidden" name="currency_code" value="USD">
        <input type="submit" class="btn btn-primary" name="submit" value="Buy Now" alt="PayPal - The safer, easier way to pay online!">


      </form>
      <img src="images/paypal-badge.png" class="pp-badge" alt="Payments through Paypal">

    </div>
  </div>
</div>
</div>