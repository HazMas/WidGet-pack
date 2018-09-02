<template>
  <div class="widget-wrapper">
    <img class="logo-esc" src="../../src/assets/img/logo-esports-calendar.png" alt="">
    <div class="container widget-flex-column">
      <div class="row widget-flex-row-data">
        <span class="hour-match">
          19:30h
        </span>
      </div>
      <div class="row widget-flex-row-shields">
        <div class="widget-shield-wrapper">
          <img class="widget-shield" src="../../src/assets/img/logo-mad-lions.png" alt="">
        </div>
        <div class="widget-shield-vs">
          <span>vs</span>
        </div>
        <div class="widget-shield-wrapper">
          <img class="widget-shield" src="../../src/assets/img/logo-kiyf.png" alt="">
        </div>
      </div>
      <div class="row widget-flex-row-data">
        <div class="widget-data-match-wrapper">
          <div class="widget-data-match">
            <span>Joranada 1</span>
            <img class="widget-shield widget-data-match-shield" src="../../src/assets/img/logo-lol.png" alt="" style="right:40%;">
            <img class="widget-shield widget-data-match-shield" src="../../src/assets/img/logo-esl.png" alt="" style="right: 10%;">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import bootstrap from '../../node_modules/bootstrap/scss/bootstrap.scss'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.logo-esc {
  position: absolute;
  top: 3%;
  left: 3%;
  height: 20%;
  width: auto;
}
.widget-wrapper {
  position: absolute;
  height: 100%;
  width: 100%;
  top: 0;
  left: 0;
  background-image: url("../../src/assets/img/bg-lol.jpg");
  background-size: cover;
  background-position: center center;
  color: white;
  height: 100%;
}
.widget-flex-column {
  padding-top: 5%;
  padding-bottom: 5%;
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100%;
}
.widget-flex-row-data {
  height: 25%;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}
.hour-match{
  font-size: 10vh;
  font-weight: 700;
}
.widget-flex-row-shields {
  height: 50%;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  width: 100%
}
.widget-shield-wrapper {
  height: 100%;
  width: 45%;
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 3%;
  padding-bottom: 3%;
}
.widget-shield-vs {
  font-size: 10vh;
  font-weight: 700;
  height: 100%;
  width: 10%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.widget-shield {
  height: 100%;
  width: auto;
}
.widget-data-match-wrapper {
  padding: 5% 20%;
  width: 100%;
}
.widget-data-match {
  font-size: 5vh;
  font-weight: bold;
  background-color: #3882EE;
  padding: 2% 7%;
  position: relative;
  border-radius: 6px;
}
.widget-data-match-shield{
  position: absolute;
  height: 150%;
  top: -25%;
}

</style>
