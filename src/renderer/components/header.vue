<template>
  <header class="h-12 align-center contents-center w-full flex bg-teal-800 font-bold uppercase text-white">
    <nav>
      <div>
        <nuxt-link
          to="/"
          exact
        >
          System info
        </nuxt-link>
      </div>
      <div>
        <nuxt-link
          to="/other"
          exact
        >
          other
        </nuxt-link>
      </div>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
    nav{
        width: 100%;
        display: flex;
        justify-content: center;
    }

    nav div{
        height: 100%;
        margin: 0 20px;
        display: flex;
        align-items: center;
    }

    a:hover{
        opacity: 0.9;
    }
</style>
