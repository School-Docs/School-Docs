<template lang="pug">
    div
        nav.fixed.w-full.top-0.h-14.border-b.w-full.backdrop-blur-md(style="background-color: rgba(241,245,249, .6); z-index: 9999;")
            .w-full.max-w-7xl.mx-auto.flex-none.flex.items-center.justify-between.h-full.px-3(class="md:px-6 lg:px-10 xl:px-16")
                nuxt-link.logoArea(to="/")
                    img.h-8(src="/logo-light.svg")
                .searchArea(class="w-4/6")
                    search
                .iconArea
                    a(href="https://github.com/School-Docs/School-Docs")
                        <i class="fab fa-github"></i>
        
        .h-16
        
        .max-w-7xl.mx-auto.mb-5.px-3(class="md:px-6 lg:px-10 xl:px-16")
            nuxt
</template>

<script>
export default {
    
}
</script>

<style lang="postcss" scoped>

</style>
