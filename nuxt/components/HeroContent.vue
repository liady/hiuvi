<template>
  <div class="pt-24 md:mb-4 lg:mb-16 xl:mb-3">
    <div class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center">
      <!--Left Col-->
      <div
        class="flex flex-col w-full md:w-2/5 justify-center items-start text-center md:text-right"
      >
        <p class="uppercase tracking-loose w-full">
          קשה לך לעקוב אחרי ההוצאות?
        </p>
        <h1 class="my-4 text-5xl font-bold leading-tight">
          <i>חיובי</i> מרכז למקום אחד את כל פירוטי ההוצאות שלך
        </h1>
        <p
          class="leading-normal text-2xl mb-8"
        >
          בצורה מאובטחת, ללא צד שלישי ובפיקוח הקהילה
        </p>

        <div class="mx-auto my-6">
          <DownloadButton button-style="bg-white text-gray-800 shadow-lg" />
        </div>
      </div>
      <!--Right Col-->
      <div class="w-full md:w-3/5 py-6 md:pr-2 text-center">
        <img
          class="w-full "
          src="~/assets/img/main-screenshot.png"
          alt
        >
      </div>
    </div>
  </div>
</template>

<script>
import DownloadButton from './DownloadButton';

export default {
  name: 'HeroContent',
  components: { DownloadButton },
};
</script>
