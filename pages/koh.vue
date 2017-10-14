<template>
  <section class="container">
    <div>
    <h1 id="head">เครื่องคำนวณหาค่าดัชนีมวลกาย (BMI)</h1><br>
    <center id="fonts">
    Weight(kg)<br>
    <input type="number" name="weight"><br><br>
    Height(cm)<br>
    <input type="number" name="eight"><br><br>
    <button class="button button2">คำนวณ</button>
    </center>
    </div>
    </section>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style>
#head{
   text-align: center;
   font-size: 60px;
   margin-top: 30 px;
   color: #2C64FE;
}
#fonts{
   text-align: center;
   font-size: 20px;
   color: #2C64FE;
}
input[type=number]{
    border: 2px solid #555;
    width: 40%;
    padding: 12px 20px;
    margin: 8px 0;
}
.button {
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 15px 40px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.button2 {
    background-color: white;
    color: black;
    border: 2px solid #008CBA;
}
</style>
