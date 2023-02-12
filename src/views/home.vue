<template>
  <div class="home-container">
    <header data-role="Header" class="home-header">
      <img
        alt="logo"
        src="/playground_assets/group-4352-2-1500h.png"
        class="home-image"
      />
      <div class="home-nav">
        <navigation-links rootClassName="rootClassName10"></navigation-links>
      </div>
      <div class="home-btn-group">
        <button class="home-login button">Login</button>
        <button class="home-register button">SCHEDULE A DEMO</button>
      </div>
      <div data-role="BurgerMenu" class="home-burger-menu">
        <svg viewBox="0 0 1024 1024" class="home-icon">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-role="MobileMenu" class="home-mobile-menu">
        <div class="home-nav1">
          <div class="home-container01">
            <img
              alt="image"
              src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
              class="home-image01"
            />
            <div data-role="CloseMobileMenu" class="home-menu-close">
              <svg viewBox="0 0 1024 1024" class="home-icon02">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <navigation-links rootClassName="rootClassName11"></navigation-links>
        </div>
        <div>
          <svg viewBox="0 0 950.8571428571428 1024" class="home-icon04">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon06">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon08">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </header>
    <div class="home-hero">
      <div class="home-container02">
        <h1 class="home-heading">IMPROVE YOUR ONLINE REPUTATION</h1>
        <span class="home-text">
          <span>
            Analyze, generate, monitor and share online reviews to improve your
            company&apos;s reputation and attract new clients.
          </span>
          <br />
          <span><span v-html="rawn5da"></span></span>
          <span><span v-html="rawo672"></span></span>
        </span>
        <div class="home-btn-group1">
          <button class="home-button button">SCHEDULE A DEMO</button>
        </div>
      </div>
      <img
        alt="image"
        src="/playground_assets/group-4319%20%5B1%5D-1500h.png"
        class="home-image02"
      />
    </div>
    <div class="home-features">
      <h1 class="home-text05">USED BY +XXX LOCAL BUSINESSES WORLDWIDE</h1>
      <div class="home-container03">
        <img
          alt="image"
          src="/playground_assets/group-4353-200h.png"
          class="home-image03"
        />
        <img
          alt="image"
          src="/playground_assets/group-4353-200h.png"
          class="home-image04"
        />
        <img
          alt="image"
          src="/playground_assets/group-4353-200h.png"
          class="home-image05"
        />
        <img
          alt="image"
          src="/playground_assets/group-4353-200h.png"
          class="home-image06"
        />
        <img
          alt="image"
          src="/playground_assets/group-4353-200h.png"
          class="home-image07"
        />
        <img
          alt="image"
          src="/playground_assets/group-4353-200h.png"
          class="home-image08"
        />
      </div>
    </div>
    <div class="home-hero1">
      <div class="home-container04">
        <span class="home-text06">GET REVIEWS</span>
        <h1 class="home-text07">
          GET NEW POSITIVE REVIEWS, AVOID THE NEGATIVE ONES
        </h1>
        <span class="home-text08">
          <span>
            Get new reviews by inviting your customers to review you via
            customizable e-mail or SMS, or on-site via QR code.
          </span>
          <br />
          <br />
          <span>
            Protect your reputation with an optional system that captures
            dissatisfied customers, keeping negative feedback private.
          </span>
          <br />
          <br />
          <span>
            Choose on which platforms you want to increase the number of positive
            reviews.
          </span>
        </span>
        <button class="home-button1 button">SCHEDULE A DEMO</button>
        <div class="home-btn-group2"></div>
      </div>
      <img
        alt="image"
        src="/playground_assets/group-3693-6%20%5B1%5D-1400w.png"
        class="home-image09"
      />
    </div>
    <div class="home-hero2">
      <img
        alt="image"
        src="/playground_assets/group-4349-2-1%20%5B1%5D-1500h.png"
        class="home-image10"
      />
      <div class="home-container05">
        <span class="home-text16">MONITOR AND REPLY</span>
        <h1 class="home-text17">
          MONITOR AND REPLY TO ALL THE REVIEWS FROM ONE PLACE.
        </h1>
        <span class="home-text18">
          <span>
            View all reviews received in the various related review platforms, day
            by day.
          </span>
          <br />
          <br />
          <span>
            Be sure to respond to all reviews you receive to show closeness to
            your customers.
          </span>
          <br />
          <br />
          <span>
            Respond to private negative feedback to regain your customers&apos;
            trust, and figure out how to improve.
          </span>
        </span>
        <button class="home-button2 button">SCHEDULE A DEMO</button>
        <div class="home-btn-group3"></div>
      </div>
    </div>
    <div class="home-hero3">
      <div class="home-container06">
        <span class="home-text26">
          <span>SHARE REVIEWS</span>
          <br />
        </span>
        <h1 class="home-text29">
          SHOW YOUR BEST REVIEWS ON YOUR WEBSITE AND SOCIAL MEDIA CHANNELS.
        </h1>
        <span class="home-text30">
          <span>
            Create a carousel or feed of your best reviews and easily post them on
            your site.
          </span>
          <br />
          <br />
          <span>
            Share the best reviews on your Facebook or Instagram page via
            customizable templates.
          </span>
          <br />
          <br />
          <span>
            Schedule the posting of reviews on social to create your own
            review-based marketing strategy.
          </span>
        </span>
        <button class="home-button3 button">SCHEDULE A DEMO</button>
        <div class="home-btn-group4"></div>
      </div>
      <img
        alt="image"
        src="/playground_assets/group-4349%20%5B1%5D-1400w.png"
        class="home-image11"
      />
    </div>
    <div class="home-hero4">
      <div class="home-container07">
        <h1 class="home-text38">YOUR NEW REVIEW MANAGEMENT PLATFORM</h1>
        <span class="home-text39">
          <span>STOP WASTING TIME TO MANAGE YOUR REVIEWS.</span>
          <span><span v-html="rawn5ao"></span></span>
          <span><span v-html="raw6vsz"></span></span>
        </span>
      </div>
      <img
        alt="image"
        src="/playground_assets/group-4295-4%20%5B1%5D-1500h.png"
        class="home-image12"
      />
      <h1 class="home-text43">START TODAY</h1>
      <button class="home-button4 button">SCHEDULE A DEMO</button>
    </div>
    <footer class="home-footer">
      <div class="home-container08">
        <div class="home-logo">
          <img
            alt="logo"
            src="/playground_assets/group-4352-2-1500h.png"
            class="home-image13"
          />
          <span class="home-text44">
            <span>
              <span>
                Professional website builder
                <span v-html="raw3ueh"></span>
              </span>
              <span><span v-html="raw7ksl"></span></span>
            </span>
            <br />
            <span>for developers.</span>
          </span>
        </div>
        <div class="home-container09">
          <div class="home-container10">
            <div class="home-product-container">
              <span class="home-text50">Product</span>
              <span class="home-text51">Features</span>
              <span class="home-text52">Pricing</span>
              <span class="home-text53">Tutorials</span>
              <span class="home-text54">Releases</span>
            </div>
            <div class="home-company-container">
              <span class="home-text55">Company</span>
              <span class="home-text56">About</span>
              <span class="home-text57">Careers</span>
              <span class="home-text58">Contact</span>
              <span class="home-text59">Blog</span>
            </div>
            <div class="home-contact">
              <span class="home-text60">Contact Us</span>
              <span class="home-text61">hello@yourbiz.io</span>
              <span class="home-text62">+123 (4567) 890</span>
              <div class="home-socials">
                <span class="home-text63">Follow Us</span>
              </div>
              <div class="home-icon-group1">
                <svg viewBox="0 0 950.8571428571428 1024" class="home-icon10">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path></svg
                ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon12">
                  <path
                    d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
                  ></path></svg
                ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon14">
                  <path
                    d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="home-separator"></div>
      <span class="home-text64">2023 © Your Business, All Rights Reserved.</span>
    </footer>
  </div>
</template>

<script>
import NavigationLinks from '../components/navigation-links'

export default {
  name: 'Home',
  components: {
    NavigationLinks,
  },
  data() {
    return {
      rawn5da: ' ',
      rawo672: ' ',
      rawn5ao: ' ',
      raw6vsz: ' ',
      raw3ueh: ' ',
      raw7ksl: ' ',
    }
  },
  metaInfo: {
    title: 'Boost Your Online Reputation with Climbo',
    meta: [
      {
        name: 'description',
        content:
          'Easily manage and monitor your online reviews with Climbo. Collect feedback from Google, Facebook, and other more to improve your business reputation.',
      },
      {
        property: 'og:title',
        content: 'Boost Your Online Reputation with Climbo',
      },
      {
        property: 'og:description',
        content:
          'Easily manage and monitor your online reviews with Climbo. Collect feedback from Google, Facebook, and other more to improve your business reputation.',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: var(--dl-color-gray-white);
}
.home-header {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
}
.home-image {
  height: 2rem;
}
.home-nav {
  display: flex;
}
.home-btn-group {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-login {
  border-width: 0px;
  margin-right: var(--dl-space-space-twounits);
}
.home-register {
  color: var(--dl-color-gray-white);
  width: var(--dl-size-size-xxlarge);
  text-align: center;
  border-radius: 20px;
  background-color: rgb(0, 0, 0);
}
.home-burger-menu {
  display: none;
}
.home-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: absolute;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff;
}
.home-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-container01 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.home-image01 {
  height: 2rem;
}
.home-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-icon02 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-hero {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  min-height: 40vh;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-container02 {
  display: flex;
  margin-right: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-heading {
  font-size: 2rem;
  max-width: 450px;
}
.home-text {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.home-btn-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-button {
  color: var(--dl-color-gray-white);
  width: 100%;
  text-align: center;
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-gray-black);
}
.home-button:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-success-500);
}
.home-image02 {
  width: 600px;
  object-fit: cover;
}
.home-features {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  flex-direction: column;
}
.home-text05 {
  font-size: 1.5rem;
  text-align: center;
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-container03 {
  gap: var(--dl-space-space-sixunits);
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-self: stretch;
  align-items: center;
  justify-content: center;
}
.home-image03 {
  width: 100px;
  object-fit: cover;
}
.home-image04 {
  width: 100px;
  object-fit: cover;
}
.home-image05 {
  width: 100px;
  object-fit: cover;
}
.home-image06 {
  width: 100px;
  object-fit: cover;
}
.home-image07 {
  width: 100px;
  object-fit: cover;
}
.home-image08 {
  width: 100px;
  object-fit: cover;
}
.home-hero1 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  min-height: 80vh;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-container04 {
  display: flex;
  margin-right: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-text06 {
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text07 {
  font-size: 2rem;
  max-width: 450px;
}
.home-text08 {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.home-button1 {
  color: var(--dl-color-gray-white);
  width: 100%;
  text-align: center;
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  border-width: 0px;
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-gray-black);
}
.home-button1:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-success-500);
}
.home-btn-group2 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-image09 {
  width: 600px;
  align-self: flex-end;
  object-fit: cover;
}
.home-hero2 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  min-height: 80vh;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-image10 {
  width: 600px;
  align-self: flex-end;
  object-fit: cover;
}
.home-container05 {
  display: flex;
  margin-right: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-text16 {
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text17 {
  font-size: 2rem;
  max-width: 450px;
  align-self: stretch;
}
.home-text18 {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.home-button2 {
  color: var(--dl-color-gray-white);
  width: 100%;
  text-align: center;
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  border-width: 0px;
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-gray-black);
}
.home-button2:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-success-500);
}
.home-btn-group3 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-hero3 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  min-height: 80vh;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-container06 {
  display: flex;
  margin-right: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-text26 {
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text29 {
  font-size: 2rem;
  max-width: 450px;
}
.home-text30 {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.home-button3 {
  color: var(--dl-color-gray-white);
  width: 100%;
  text-align: center;
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  border-width: 0px;
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-gray-black);
}
.home-button3:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-success-500);
}
.home-btn-group4 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-image11 {
  width: 600px;
  align-self: flex-end;
  object-fit: cover;
}
.home-hero4 {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  min-height: 130vh;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #f7f7f7;
}
.home-container07 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text38 {
  font-size: 3rem;
}
.home-text39 {
  margin-top: var(--dl-space-space-twounits);
  text-align: center;
  padding-left: var(--dl-space-space-threeunits);
  margin-bottom: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-threeunits);
}
.home-image12 {
  width: 100%;
  margin-top: var(--dl-space-space-twounits);
}
.home-text43 {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.home-button4 {
  color: var(--dl-color-gray-white);
  width: 550px;
  text-align: center;
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  border-width: 0px;
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  margin-bottom: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-gray-black);
}
.home-button4:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-success-500);
}
.home-footer {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  justify-content: space-between;
  background-color: var(--dl-color-gray-black);
}
.home-container08 {
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-direction: row;
  justify-content: space-between;
}
.home-logo {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-image13 {
  height: 2rem;
}
.home-text44 {
  color: var(--dl-color-gray-white);
  margin-top: var(--dl-space-space-oneandhalfunits);
}
.home-container09 {
  display: flex;
}
.home-container10 {
  gap: var(--dl-space-space-fourunits);
  display: flex;
}
.home-product-container {
  width: 150px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text50 {
  color: var(--dl-color-gray-white);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text51 {
  color: var(--dl-color-gray-white);
  margin-bottom: var(--dl-space-space-unit);
}
.home-text52 {
  color: var(--dl-color-gray-white);
  margin-bottom: var(--dl-space-space-unit);
}
.home-text53 {
  color: var(--dl-color-gray-white);
  margin-bottom: var(--dl-space-space-unit);
}
.home-text54 {
  color: var(--dl-color-gray-white);
}
.home-company-container {
  width: 150px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text55 {
  color: var(--dl-color-gray-white);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text56 {
  color: var(--dl-color-gray-white);
  margin-bottom: var(--dl-space-space-unit);
}
.home-text57 {
  color: var(--dl-color-gray-white);
  margin-bottom: var(--dl-space-space-unit);
}
.home-text58 {
  color: var(--dl-color-gray-white);
  margin-bottom: var(--dl-space-space-unit);
}
.home-text59 {
  color: var(--dl-color-gray-white);
}
.home-contact {
  width: 150px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text60 {
  color: var(--dl-color-gray-white);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text61 {
  color: var(--dl-color-gray-white);
  margin-bottom: var(--dl-space-space-unit);
}
.home-text62 {
  color: var(--dl-color-gray-white);
}
.home-socials {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text63 {
  color: var(--dl-color-gray-white);
  margin-top: var(--dl-space-space-twounits);
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-icon-group1 {
  fill: white;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-icon10 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-unit);
}
.home-icon12 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-unit);
}
.home-icon14 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-separator {
  width: 100%;
  height: 1px;
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
  background-color: var(--dl-color-gray-white);
}
.home-text64 {
  color: var(--dl-color-gray-white);
  align-self: center;
}
@media(max-width: 1200px) {
  .home-text38 {
    align-self: center;
    text-align: center;
  }
  .home-container10 {
    gap: 0;
  }
  .home-contact {
    margin-right: var(--dl-space-space-twounits);
  }
}
@media(max-width: 991px) {
  .home-hero {
    flex-direction: column;
  }
  .home-container02 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .home-heading {
    text-align: center;
  }
  .home-text {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-features {
    align-items: stretch;
  }
  .home-text05 {
    align-self: center;
  }
  .home-container03 {
    gap: var(--dl-space-space-threeunits);
    width: 100%;
    flex-wrap: wrap;
  }
  .home-hero1 {
    flex-direction: column;
  }
  .home-container04 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .home-text07 {
    max-width: 800px;
    text-align: center;
  }
  .home-text08 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-image09 {
    width: 100%;
  }
  .home-hero2 {
    flex-direction: column;
  }
  .home-image10 {
    width: 100%;
  }
  .home-container05 {
    margin-top: var(--dl-space-space-twounits);
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .home-text17 {
    align-self: center;
    text-align: center;
  }
  .home-text18 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-hero3 {
    flex-direction: column;
  }
  .home-container06 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .home-text29 {
    text-align: center;
  }
  .home-text30 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-image11 {
    width: 100%;
  }
  .home-hero4 {
    flex-direction: column;
  }
  .home-container07 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-text38 {
    text-align: center;
  }
  .home-text39 {
    text-align: center;
  }
  .home-image12 {
    width: 80%;
  }
  .home-footer {
    flex-direction: column;
  }
  .home-container08 {
    gap: var(--dl-space-space-fourunits);
    flex-direction: column;
    justify-content: space-between;
  }
  .home-logo {
    align-items: center;
  }
}
@media(max-width: 767px) {
  .home-header {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-nav {
    display: none;
  }
  .home-btn-group {
    display: none;
  }
  .home-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .home-icon {
    width: var(--dl-size-size-medium);
  }
  .home-hero {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-text {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-image02 {
    width: 80%;
  }
  .home-features {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-hero1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-container04 {
    align-self: center;
    align-items: flex-start;
  }
  .home-text06 {
    align-self: center;
  }
  .home-text07 {
    align-self: center;
    text-align: center;
  }
  .home-text08 {
    text-align: center;
    padding-left: 0px;
    padding-right: var(--dl-space-space-halfunit);
  }
  .home-image09 {
    width: 100%;
    align-self: center;
  }
  .home-hero2 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-image10 {
    width: 100%;
    align-self: center;
  }
  .home-container05 {
    align-self: center;
    margin-top: var(--dl-space-space-twounits);
    align-items: flex-start;
  }
  .home-text16 {
    align-self: center;
    text-align: center;
  }
  .home-text17 {
    align-self: center;
    text-align: center;
  }
  .home-text18 {
    text-align: center;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-button2 {
    align-self: center;
  }
  .home-hero3 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-container06 {
    align-self: center;
    align-items: flex-start;
  }
  .home-text26 {
    align-self: center;
    text-align: center;
  }
  .home-text29 {
    align-self: center;
  }
  .home-text30 {
    align-self: center;
    text-align: center;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-image11 {
    width: 80%;
    align-self: center;
  }
  .home-hero4 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-text39 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-footer {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-logo {
    align-items: center;
  }
  .home-image13 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-text44 {
    margin-top: var(--dl-space-space-twounits);
    text-align: center;
    margin-bottom: var(--dl-space-space-twounits);
  }
}
@media(max-width: 479px) {
  .home-header {
    padding: var(--dl-space-space-unit);
  }
  .home-icon {
    width: var(--dl-size-size-small);
    height: 30px;
  }
  .home-mobile-menu {
    padding: 16px;
  }
  .home-hero {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container02 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text {
    font-size: 18px;
  }
  .home-btn-group1 {
    flex-direction: column;
  }
  .home-features {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container03 {
    flex-wrap: wrap;
    justify-content: center;
  }
  .home-hero1 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container04 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text06 {
    font-size: 18px;
    align-self: center;
    text-align: center;
  }
  .home-text07 {
    font-size: 1.5rem;
    text-align: center;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-text08 {
    font-size: 18px;
    text-align: left;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-button1 {
    width: 100%;
    align-self: center;
    text-align: center;
  }
  .home-btn-group2 {
    flex-direction: column;
  }
  .home-image09 {
    align-self: center;
  }
  .home-hero2 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-image10 {
    align-self: center;
  }
  .home-container05 {
    padding-top: var(--dl-space-space-twounits);
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text16 {
    font-size: 18px;
    align-self: center;
  }
  .home-text17 {
    font-size: 1.5rem;
    align-self: center;
    text-align: center;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-text18 {
    font-size: 18px;
    text-align: left;
  }
  .home-button2 {
    width: 100%;
    align-self: center;
    text-align: center;
  }
  .home-btn-group3 {
    flex-direction: column;
  }
  .home-hero3 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container06 {
    padding-top: var(--dl-space-space-twounits);
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text26 {
    font-size: 18px;
    align-self: center;
  }
  .home-text29 {
    font-size: 1.5rem;
    text-align: center;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-text30 {
    font-size: 18px;
    text-align: left;
  }
  .home-button3 {
    width: 100%;
    align-self: center;
    text-align: center;
  }
  .home-btn-group4 {
    flex-direction: column;
  }
  .home-image11 {
    align-self: center;
  }
  .home-hero4 {
    min-height: 80vh;
    padding-top: var(--dl-space-space-unit);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-unit);
  }
  .home-container07 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text38 {
    font-size: 2rem;
  }
  .home-text39 {
    font-size: 18px;
  }
  .home-button4 {
    width: 100%;
    align-self: center;
    text-align: center;
  }
  .home-footer {
    padding: var(--dl-space-space-unit);
  }
  .home-container08 {
    width: 100%;
  }
  .home-logo {
    width: auto;
    align-items: center;
  }
  .home-image13 {
    margin-bottom: 0px;
  }
  .home-text44 {
    margin-top: var(--dl-space-space-twounits);
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-container09 {
    position: relative;
    flex-wrap: wrap;
    flex-direction: column;
  }
  .home-container10 {
    flex-wrap: wrap;
    align-self: stretch;
    justify-content: space-between;
  }
  .home-company-container {
    margin-top: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-unit);
  }
  .home-contact {
    margin-top: var(--dl-space-space-twounits);
    align-items: flex-start;
    margin-right: var(--dl-space-space-unit);
    margin-bottom: 0px;
  }
  .home-text63 {
    margin-top: var(--dl-space-space-unit);
  }
  .home-text64 {
    text-align: center;
  }
}
</style>
