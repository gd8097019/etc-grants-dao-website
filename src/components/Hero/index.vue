<template>
    <section id="hero">
        <div
          class="bg-[url('@/images/heroBgMobile.svg')] grid-cols-1 heroSection grid md:grid-cols-2 bg-no-repeat bg-contain md:bg-cover min-h-heroHeight sm:bg-[url('@/images/heroBg.svg')]">
          <div
            class="my-auto mx-auto md:mx-0 md:my-0 text-center md:text-left container md:pl-8 xl:pl-28 md:pr-0 pt-11 content-end">
            <h1
              class="pl-heroHeadingMobile pr-heroHeadingMobile md:pl-0 md:pr-0 text-fourty leading-heroHeadingMobile text-headingsColor md:text-xxl md:leading-heroHeadingDesktop font-bold font-notoSans">
              {{ $t("etc-grants-dao.title") }}
            </h1>
            <div class="pt-6"/>
            <p
              class="text-heroTextMobile md:text-heroTextDesktop text-headingsColor leading-heroText pt-1 pb-6 font-dmSans pl-8 pr-8 md:pl-0 md:pr-0">
              {{ $t("etc-grants-dao.description") }}
              <div class="pt-6"/>
              <img :src="$t('etc-grants-dao.key-dates-link')"/>
              <div class="pt-6"/>
              <div class="inline-block">
                <a 
                  :href="$t('etc-grants-dao.apply-now-link')"
                  class="relative lg:block font-notoSans font-semibold px-5 py-2 rounded text-headingsColor border-2 text-lg topApplyNow bg-gradient-to-r from-[#ff0000] to-[#581b1b]">
                  {{ $t("etc-grants-dao.apply-now-text") }}
                </a>
              </div>
            </p>
          </div>
          <div class="hidden md:block"></div>
        </div>
      </section>
</template>

<script>
export default {
    name: 'HeroSection'
}
</script>
