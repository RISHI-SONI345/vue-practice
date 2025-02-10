<!-- <script setup>
import { ref, computed } from 'vue';

const number = ref(5);

// Computed Property
const squared = computed(() => {
  return number.value * number.value;
});

// Method
const squareMethod = () => {
  return number.value * number.value;
};
</script>

<template>
  <p>Number: {{ number }}</p>
  <p>Computed Square: {{ squared }}</p>
  <p>Method Square: {{ squareMethod() }}</p>
</template> -->


<!-- to real time sync with user data btw input field and vue data we use v-model -->
<!-- 
<script setup>
import { ref } from 'vue';
const username=ref("");

</script>

<template>
<input v-model="username" placeholder="enter your name">
<p>this is your name:{{ username }} </p>

</template> -->

<!-- 
<script setup>
import { ref } from 'vue';

const isRed = ref(false);
</script>

<template>
  <button :class="{ red: isRed }" @click="isRed = !isRed">
    Toggle Color
  </button>
</template>

<style>
.red {
  background-color: red;
  color: white;
}
</style> -->

<!-- <script setup>
import { ref } from 'vue';


const showmessage=ref("this is the message")

</script>

<template>
  <button @click="showmessage=!showmessage">toggle</button>
  <p v-if="showmessage">This message is visible</p>
</template> -->











<!-- <script setup>
import { ref } from 'vue';
import HelloWorld from './components/HelloWorld.vue';
const lists=ref(["alice","bob","charlie"]);



</script>

<template>

  <ul >
    <li v-for=" (name,index) in lists" :key="index">
      {{ name }}

    </li>
  </ul>

  <div>
    <HelloWorld/>
  </div>
</template> -->



<!-- this is the code for  the props -->

<!-- <script setup>



</script>


<template>

</template> -->

<!-- router -->

<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>

  <router-view></router-view>
</template>
