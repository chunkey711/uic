<template>
  <div class="container">
    <div>
      <div class="cards">
        <img src="@/assets/main_bg.png">
      </div>
      <div>
        <h1>Welcome</h1>
        <p>Lorem ipsum dolor sit amet, 
          consectetur adipiscing</p>
        <ComponentButton text='Get Started'/>
      </div>
      <div>
        <a href="" class="login">Log In</a>
      </div>
    </div>
  </div>
</template>


<script>
import ComponentButton from '@/components/Button'
export default {
  components: {
    ComponentButton
  }
}
</script>

<style lang="scss" scoped>

.cards {
  padding-top: 35px;
  width: 100%;
  img {
    width: 100%;
    height: auto;
  }
}

h1 {
  font-size: 30px;
  text-align: center;
  font-family: 'Zilla Slab', serif;
  color: rgba(255,255,255,1);
  margin: 1rem 0;
}

p {
  font-family: sans-serif;
  text-align: center;
  font-size: 19px;
  color: rgba(255,255,255,0.7);
}

.login {
  font-family: 'Gotham';
  text-decoration: underline;
  font-size: 18px;
  text-decoration: underline;
  color: rgba(255,255,255,0.7);
  display: inherit;
  text-align: center;
  text-align: center;
  margin-top: 80px;
}
</style>
