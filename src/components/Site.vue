<template>
  <div>
    <h1 class="abs">Система Інвентаризації</h1>
    <p class="about">
      IO — це система інвентаризації розроблена для
      ведення електронного обліку обладнання та
      ліцензій програмного забезпечення на підприємстві.
    </p>
    <v-btn class="btn-start1"
           v-for="starts in start"
           :key="starts"
           text
           color=#FFFFFF
           rounded
    >
      {{ starts }}
    </v-btn>
    </div>
</template>

<script>
export default {
  data: () => ({
    start: [
      'Увiйти',
    ],
  }),
}
</script>

<style>
.abs{
  display: flex;
  position: absolute;
  width: 480px;
  height: 57px;
  left: 241px;
  top: 190px;

  font-family: Nunito;
  font-style: normal;
  font-weight: bold;
  font-size: 42px;
  line-height: 57px;

  color: #000000;
}
.about{
  display: flex;
  flex-direction: column;
  position: absolute;
  width: 731px;
  height: 196px;
  left: 241px;
  top: 277px;

  font-family: Nunito;
  font-style: normal;
  font-weight: normal;
  font-size: 36px;
  line-height: 49px;

  color: #000000;
}
.btn-start1 {
  display: flex;
  position: absolute;
  width: 220px;
  height: 50px;
  left: 240px;
  top: 503px;
  background: #7683F7;
  border-radius: 15px;
  font-family: Nunito;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 25px;
  align-content: center;
  /* identical to box height */


  color: #FFFFFF;

}
</style>
