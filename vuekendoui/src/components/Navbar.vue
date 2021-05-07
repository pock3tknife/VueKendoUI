<template>
  <nav class="nav-menu">
    <ul>
      <li><a href="/">Home</a></li>
      <li id="services">
        <a href="/grid">Grid</a>
        <div class="sub-nav">
          <div class="sub-nav-col left">
            <a
              href="/grid/editing-custom-template"
              class="sub-nav-box"
              id="box-1"
            >
              <div class="icon-background" id="icon-1">
                <i class="fab fa-sellsy icon"></i>
              </div>
              <h4>Custom Editing in Reactive Forms</h4>
              <p>Dedicated ad platform</p>
            </a>
            <a href="#" class="sub-nav-box" id="box-2">
              <div class="icon-background" id="icon-2">
                <i class="fas fa-user-lock icon"></i>
              </div>
              <h4>Consulting</h4>
              <p>24/7 support team</p>
            </a>
            <a href="#" class="sub-nav-box" id="box-3">
              <div class="icon-background" id="icon-3">
                <i class="fas fa-chart-line icon"></i>
              </div>
              <h4>Investing</h4>
              <p>Financial planning & risk</p>
            </a>
            <a href="#" class="sub-nav-box" id="box-4">
              <div class="icon-background" id="icon-4">
                <i class="fas fa-hand-holding-usd icon"></i>
              </div>
              <h4>Funding</h4>
              <p>Kickstart your idea</p>
            </a>
          </div>
          <div class="sub-nav-col right">
            <a href="#" class="sub-nav-box" id="box-5">
              <div class="icon-background" id="icon-5">
                <i class="fas fa-trophy icon"></i>
              </div>
              <h4>Goals</h4>
              <p>Monthly tracking</p>
            </a>
            <a href="#" class="sub-nav-box" id="box-6">
              <div class="icon-background" id="icon-6">
                <i class="far fa-calendar-check icon"></i>
              </div>
              <h4>Onboarding</h4>
              <p>Get started quickly</p>
            </a>
            <a href="#" class="sub-nav-box" id="box-7">
              <div class="icon-background" id="icon-7">
                <i class="fas fa-briefcase icon"></i>
              </div>
              <h4>Resources</h4>
              <p>FAQ questions</p>
            </a>
            <a href="#" class="sub-nav-box" id="box-8">
              <div class="icon-background" id="icon-8">
                <i class="fas fa-phone-alt icon"></i>
              </div>
              <h4>Support</h4>
              <p>Contact a specialist</p>
            </a>
          </div>
        </div>
      </li>
      <li id="charts">
        <a href="/">Charts</a>
        <div class="sub-nav2">
          <div class="sub-nav-col2 left">
            <a href="#" class="sub-nav-box2" id="box2-1">
              <div class="icon-background" id="icon2-1">
                <i class="fab fa-sellsy icon"></i>
              </div>
              <h4>Stock Chart</h4>
              <p>Dedicated ad platform</p>
            </a>
            <a href="#" class="sub-nav-box2" id="box2-2">
              <div class="icon-background" id="icon2-2">
                <i class="fas fa-user-lock icon"></i>
              </div>
              <h4>Consulting</h4>
              <p>24/7 support team</p>
            </a>
            <a href="#" class="sub-nav-box2" id="box2-3">
              <div class="icon-background" id="icon2-3">
                <i class="fas fa-chart-line icon"></i>
              </div>
              <h4>Investing</h4>
              <p>Financial planning & risk</p>
            </a>
            <a href="#" class="sub-nav-box2" id="box2-4">
              <div class="icon-background" id="icon2-4">
                <i class="fas fa-hand-holding-usd icon"></i>
              </div>
              <h4>Funding</h4>
              <p>Kickstart your idea</p>
            </a>
          </div>
          <div class="sub-nav-col2 right">
            <a href="#" class="sub-nav-box2" id="box2-5">
              <div class="icon-background" id="icon2-5">
                <i class="fas fa-trophy icon"></i>
              </div>
              <h4>Goals</h4>
              <p>Monthly tracking</p>
            </a>
            <a href="#" class="sub-nav-box2" id="box2-6">
              <div class="icon-background" id="icon2-6">
                <i class="far fa-calendar-check icon"></i>
              </div>
              <h4>Onboarding</h4>
              <p>Get started quickly</p>
            </a>
            <a href="#" class="sub-nav-box2" id="box2-7">
              <div class="icon-background" id="icon2-7">
                <i class="fas fa-briefcase icon"></i>
              </div>
              <h4>Resources</h4>
              <p>FAQ questions</p>
            </a>
            <a href="#" class="sub-nav-box2" id="box2-8">
              <div class="icon-background" id="icon2-8">
                <i class="fas fa-phone-alt icon"></i>
              </div>
              <h4>Support</h4>
              <p>Contact a specialist</p>
            </a>
          </div>
        </div>
      </li>
      <li><a href="/">TreeView</a></li>
      <li><a href="/">Editor</a></li>
      <li><a href="/">Sign up</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "navbar",
  components: {},
};
</script>

<style>
.nav-menu {
  display: inline-block;
  vertical-align: top;
  margin-top: 22px;
  margin-left: 50px;
}

ul {
  font-size: 13px;
  line-height: 21px;
}

li:first-child {
  margin-left: 0;
}

li {
  display: inline-block;
  margin-left: 28px;
  padding-bottom: 22px;
  position: relative;
}

li > a {
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  text-decoration: none;
  color: #252222;
  font-weight: bold;
}

.sub-nav {
  background: #f7f7f7;
  border-radius: 5px;
  box-shadow: 0 10px 8px 0 rgba(0, 0, 0, 0.2);
  display: none;
  left: -120px;
  padding: 16px;
  position: absolute;
  top: 100%;
  width: 628px;
}

.sub-nav2 {
  background: #f7f7f7;
  border-radius: 5px;
  box-shadow: 0 10px 8px 0 rgba(0, 0, 0, 0.2);
  display: none;
  left: -120px;
  padding: 16px;
  position: absolute;
  top: 100%;
  width: 628px;
}

#services:hover .sub-nav {
  display: flex;
}

#charts:hover .sub-nav2 {
  display: flex;
}

.sub-nav-col {
  display: flex;
  flex-direction: column;
  flex: 1;
  max-width: 50%;
}

.sub-nav-col2 {
  display: flex;
  flex-direction: column;
  flex: 1;
  max-width: 50%;
}

.left {
  margin-right: 4px;
}

.right {
  margin-left: 4px;
}

.sub-nav-box {
  background: #fff;
  border-radius: 3px;
  display: flex;
  flex: 0 1 auto;
  flex-direction: column;
  font-size: 14px;
  justify-content: center;
  margin: 4px 0;
  min-height: 100px;
  padding: 24px 14px 24px 96px;
  position: relative;
  transition: 0.2s all ease-in-out;
  text-decoration: none;
}

.sub-nav-box2 {
  background: #fff;
  border-radius: 3px;
  display: flex;
  flex: 0 1 auto;
  flex-direction: column;
  font-size: 14px;
  justify-content: center;
  margin: 4px 0;
  min-height: 100px;
  padding: 24px 14px 24px 96px;
  position: relative;
  transition: 0.2s all ease-in-out;
  text-decoration: none;
}

.icon-background {
  height: 64px;
  width: 64px;
  background: #252222;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  left: 14px;
}

.icon {
  color: #fff;
  font-size: 20px;
}

.sub-nav-box h4 {
  font-size: 12px;
  letter-spacing: 0.9px;
  line-height: 16px;
  margin: 0 0 0.5em;
  padding: 0;
  text-transform: uppercase;
  color: #292d34;
}

.sub-nav-box2 h4 {
  font-size: 12px;
  letter-spacing: 0.9px;
  line-height: 16px;
  margin: 0 0 0.5em;
  padding: 0;
  text-transform: uppercase;
  color: #292d34;
}

.sub-nav-box p {
  color: #292d34;
  line-height: 16px;
}

.sub-nav-box2 p {
  color: #292d34;
  line-height: 16px;
}

.sub-nav::after {
  bottom: 100%;
  left: 140px;
  content: "";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
  border: solid transparent;
  border-color: rgba(252, 252, 252, 0);
  border-bottom-color: #f7f7f7;
  border-width: 20px;
  border-radius: 2px;
  margin-left: -20px;
}

.sub-nav2::after {
  bottom: 100%;
  left: 140px;
  content: "";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
  border: solid transparent;
  border-color: rgba(252, 252, 252, 0);
  border-bottom-color: #f7f7f7;
  border-width: 20px;
  border-radius: 2px;
  margin-left: -20px;
}

.sub-nav-box:hover h4,
.sub-nav-box:hover p {
  color: #fff;
  font-weight: bold;
}

.sub-nav-box2:hover h4,
.sub-nav-box2:hover p {
  color: #fff;
  font-weight: bold;
}

#box-1:hover,
#icon-1 {
  background: #7e3ef3;
}

#box2-1:hover,
#icon2-1 {
  background: #7e3ef3;
}

#box-2:hover,
#icon-2 {
  background: #fe4242;
}

#box2-2:hover,
#icon2-2 {
  background: #fe4242;
}

#box-3:hover,
#icon-3 {
  background: #2ee1f9;
}

#box-3:hover,
#icon-3 {
  background: #2ee1f9;
}

#box2-4:hover,
#icon2-4 {
  background: #2ef968;
}

#box-5:hover,
#icon-5 {
  background: #ffcf11;
}

#box2-5:hover,
#icon2-5 {
  background: #ffcf11;
}

#box-6:hover,
#icon-6 {
  background: #86ffc6;
}

#box2-6:hover,
#icon2-6 {
  background: #86ffc6;
}

#box-7:hover,
#icon-7 {
  background: #ff60b2;
}

#box2-7:hover,
#icon2-7 {
  background: #ff60b2;
}

#box-8:hover,
#icon-8 {
  background: #5462ff;
}

#box2-8:hover,
#icon2-8 {
  background: #5462ff;
}
</style>
