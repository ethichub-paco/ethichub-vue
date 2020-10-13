<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-item menu-text">Resume</div>
      <div class="menu-item menu-text">Skaiting</div>
      <div class="menu-item menu-center">EthicHub</div>
      <div class="menu-item menu-text">Youtube</div>
      <div class="menu-item menu-text">About</div>
    </div>

    <div class="name">
      <!-- <div class="letter">
        <img src="../assets/img/E.jpg" class="letter-image" />
      </div>
      <div class="letter">
        <img src="../assets/img/t.jpg" class="letter-image" />
      </div> -->
      <div class="letter">
        <img src="../assets/img/i.jpg" class="letter-image" />
      </div>
      <div class="letter">
        <img src="../assets/img/c.jpg" class="letter-image" />
      </div>
      <div class="letter">
        <img src="../assets/img/H.jpg" class="letter-image" />
      </div>
      <div class="letter">
        <img src="../assets/img/u.jpg" class="letter-image" />
      </div>
      <div class="letter">
        <img src="../assets/img/b.jpg" class="letter-image" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style scoped>
.name {
  /* border: 1px solid red; */
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  margin-top: 30px;
  width: 98.7vw;
  height: 100vm;
}
.letter {
  margin: 1px;
  filter: drop-shadow(0px 0px 5px rgba(255, 255, 255, 7));
}

.letter-image {
  width: 100%;
}

.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
}

.menu-item {
  flex: 1;
  text-align: center;
}

.menu-text{
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
}

.menu-text:hover {
  border-bottom: 2px solid #c278ff;
}

.menu-center {
  font-size: 36px;
  color: #EAEAEA;
}
</style>
