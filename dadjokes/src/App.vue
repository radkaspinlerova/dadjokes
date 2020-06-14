<template>
  <div>
    <div class="container">
      <div class="joke">
        <div class="joke__body">
          <img class="joke__user" src="assets/img/user01.png" />
          <p
            class="joke__text"
          >The secret service isn't allowed to yell "Get down!" anymore when the president is about to be attacked. Now they have to yell "Donald, duck!"</p>
        </div>
        <div class="joke__likes">
          <button id="btn-up" class="btn-like btn-like--up"></button>
          <span id="likes-up" class="likes-count likes-count--up">0</span>
          <button id="btn-down" class="btn-like btn-like--down"></button>
          <span id="likes-down" class="likes-count likes-count--down">0</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style scoped></style>
