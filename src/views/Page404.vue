<template>
    <div class="h-screen w-screen flex flex-col justify-center items-center bg-cover bg-center bg-no-repeat bg-[url('/images/background/bg404.gif')]">
    	<h1 class="text-9xl font-extrabold text-white tracking-widest">404</h1>
    	<div class="bg-web-boton px-2 text-sm rounded rotate-12 absolute">
    		Página no encontrada
    	</div>
    	<router-link to="/" class="mt-5">
          <a
            class="relative inline-block text-base font-medium text-web-boton group active:text-orange-500 focus:outline-none focus:ring"
          >
            <span
              class="absolute inset-0 transition-transform translate-x-0.5 translate-y-0.5 bg-web-boton group-hover:translate-y-0 group-hover:translate-x-0"
            ></span>

            <span class="relative block px-8 py-3 bg-gray-900 hover:bg-gray-600 border border-current">
              Volver al inicio
            </span>
          </a>
        </router-link>
    </div>

</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>