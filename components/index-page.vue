<template lang="pug">
    div
        .title.my-10
            h1.text-4xl.font-bold.leading-normal.tracking-tight.m-0 School-Machine Docs와 함께 시작하기
            h2.text-xl.text-gray-600.mt-3 School-Machine Docs 이용 가이드를 탐색하고, 이용 도중 발생한 문제를 해결하세요.

        hr

        .my-10.grid.grid-cols-1.gap-4(class="lg:grid-cols-2")
            .flex.flex-col.gap-5
                h2.font-bold.pt-5.text-3xl.mt-0.mb-0.tracking-tight 자주 찾는 질문
                h3.text-lg.mt-5.text-gray-500 School-Machine Docs 의 자주 찾는 질문..
                p.my-3
                    nuxt-link(to="/category/faq")
                        button.w-full.flex-none.bg-gray-900.text-white.leading-6.py-2.px-3.border.border-transparent.rounded-lg.transition.duration-200(class="sm:w-auto hover:bg-gray-700 focus:ring-offset-2 focus:ring-offset-white focus:ring-gray-900 focus:outline-none focus:ring-2")
                            | 탐색하기
                            i.fal.fa-arrow-right.ml-2
                .flex
                    span.tag.bg-gray-200.p-2.text-sm.rounded-lg.text-gray-500 School-Machine Docs
                    span.tag.bg-gray-200.p-2.text-sm.rounded-lg.text-gray-500 FAQ
                    span.tag.bg-gray-200.p-2.text-sm.rounded-lg.text-gray-500 자주 찾는 질문
            img.w-full.h-auto.overflow-hidden.rounded-md.row-start-1(class="lg:row-start-auto" src="~/assets/img/index/faq_left.jpeg")
        
        hr

        .my-10.grid.grid-cols-1.gap-8(class="lg:grid-cols-3")
            .rounded-xl.bg-gradient-to-br.from-cyan-400.to-blue-500.p-5.text-white.flex.flex-col.gap-5
                h2.font-bold.text-2xl 방송실 장비 가이드
                h3 방송실 장비 사용을 위한 꿀팁들을 모아 확인해보세요.
                .flex-grow
                nuxt-link(to="/category/tutorials/equipment1")
                    button.w-full.flex-none.bg-gray-900.bg-opacity-20.text-white.leading-6.py-2.px-3.border.border-transparent.rounded-lg.transition.duration-200(class="sm:w-auto hover:bg-gray-700 focus:ring-offset-2 focus:ring-offset-white focus:ring-gray-900 focus:outline-none focus:ring-2")
                        | 지금 확인하기
                        i.fal.fa-arrow-right.ml-2
            .rounded-xl.bg-gradient-to-br.from-yellow-400.to-orange-500.p-5.text-white.flex.flex-col.gap-5
                h2.font-bold.text-2xl 송백관 장비 가이드
                h3 송백관 장비 사용을 위한 꿀팁들을 모아 확인해보세요.
                .flex-grow
                nuxt-link(to="/category/tutorials/equipment2")
                    button.w-full.flex-none.bg-gray-900.bg-opacity-20.text-white.leading-6.py-2.px-3.border.border-transparent.rounded-lg.transition.duration-200(class="sm:w-auto hover:bg-gray-700 focus:ring-offset-2 focus:ring-offset-white focus:ring-gray-900 focus:outline-none focus:ring-2")
                        | 지금 확인하기
                        i.fal.fa-arrow-right.ml-2
            .rounded-xl.bg-gradient-to-br.from-green-400.to-green-600.p-5.text-white.flex.flex-col.gap-5
                h2.font-bold.text-2xl 기타 장비 가이드
                h3 기타 장비 사용을 위한 꿀팁들을 모아 확인해보세요.
                .flex-grow
                nuxt-link(to="/category/faq/others")
                    button.w-full.flex-none.bg-gray-900.bg-opacity-20.text-white.leading-6.py-2.px-3.border.border-transparent.rounded-lg.transition.duration-200(class="sm:w-auto hover:bg-gray-700 focus:ring-offset-2 focus:ring-offset-white focus:ring-gray-900 focus:outline-none focus:ring-2")
                        | 지금 확인하기
                        i.fal.fa-arrow-right.ml-2
        hr
</template>

<script>
export default {
    name: "index-page"
}
</script>

<style lang="postcss">
.community-icon {
    width: 50px;
    height: 50px;
    max-width: 50px;
    max-height: 50px;
    min-width: 50px;
    min-height: 50px;
    padding: 10px;
}

.tag + .tag {
    margin-left: 6px;
}
</style>