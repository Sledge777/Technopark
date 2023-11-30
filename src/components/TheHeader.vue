<template>
  <header>
    <div class="logo">
      <img src="@/assets/RGSU_logo.png" alt="Logo RGSU" class="logo__img" />
      <div class="logo__line"></div>
      <h1 class="logo__text">
        ФИЛИАЛ РГСУ В Г. ПЯТИГОРСКЕ СТАВРОПОЛЬСКОГО КРАЯ
      </h1>
      <section>
        
        <ul class="refs">
          <li>
            <a class="refs__adv" href="mailto:pjatigorsk@rgsu.net"
              ><strong>pjatigorsk@rgsu.net</strong></a
            >
          </li>
          <li>
            <a class="refs__adv" href="tel:+7 (8793) 33-60-97"
              >+7 (8793) 33-60-97</a
            >
          </li>
          <li>
            <a class="refs__adv" href="tel:+7 (928) 348-84-84"
              >+7 (928) 348-84-84</a
            >
          </li>
          <li>
            <a class="refs__adv" href="tel:+7 (495) 255-67-67"
              >+7 (495) 255-67-67, доб. 7115</a
            >
          </li>
        </ul>
      </section>
    </div>
  </header>
</template>

<script></script>

<style scoped>
header {
  width: 80%;
  margin: auto;
  margin-top: 1%;
}

.logo {
  display: flex;
  justify-content: center;
}

.logo__img {
  width: 40%;
  align-self: center;
}

.logo__line {
  width: 0.3%;
  background-color: #024a7a;
}

.logo__text {
  font-size: 1.5em;
  color: #024a7a;
  width: 30%;
  text-align: center;
  align-self: center;
}

.refs {
  color: #024a7a;
  list-style: none;
  font-size: 1.5em;
  align-self: center;
  margin-left: 2%;
  line-height: 1.2;
}

.refs__adv {
  text-decoration: none;
  color: #024a7a;
}
</style>
