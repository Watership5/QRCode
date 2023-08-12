<script setup lang="ts">
  //importing dependencies
  import qrcode from "../../public/image-qr-code.png"
</script>

<template>
  <main>
    <!-- the main html -->
    <img :src="qrcode" alt="qrcode" width="275"/>
    <p>
      Improve your front-end skills by building projects
    </p>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
    </p>
  </main>
</template>

<style>
  /* importing the font family  */
  @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');
  body{
    display: flex;
    align-items: center;
    height: 100vh;
    justify-content: center;
    background-color: hsl(212, 45%, 89%);
  }
  main{
    background-color: white;
    width: fit-content;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    font-family: "Outfit";
    padding: 1rem;
    padding-top: 1rem;
    border-radius: 15px;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
  }
  img{
    border-radius: 10px;
    margin-bottom: 0.5rem;
  }
  p{
    width: 16rem;
    text-align: center;
    font-weight: 400;
    color: hsl(220, 15%, 55%);
    font-size: 15px;
  }
  p:first-of-type{
    font-weight: 700;
    font-size: 20px;
    width: 15rem;
    margin-bottom: -1px;
    color: hsl(218, 44%, 22%);
  }
</style>
