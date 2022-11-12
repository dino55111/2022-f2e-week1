<script setup></script>

<template>
  <section class="sponsorsBlock bg-hex-cfa575 py-60px">
    <h2
      class="sponsorsBlock__title text-white text-center font-900 text-24px md:text-36px"
    >
      本次活動贊助單位
    </h2>

    <div
      class="px-16px py-30px md:flex md:justify-center md:items-center md:py-60px"
    >
      <a
        href="https://www.kdanmobile.com/zh-tw"
        class="block bg-white p-20px rounded-16px max-w-250px mx-auto"
      >
        <img
          class="w-full"
          src="@/assets/images/sponsor/KDANMobile.png"
          title="KDANMobile"
          alt="KDANMobile"
        />
      </a>
      <a
        href="https://titansoft.com/tw"
        class="block bg-white p-20px rounded-16px max-w-250px mx-auto mt-24px md:mt-0 md:ml-20px"
      >
        <img
          class="w-full"
          src="@/assets/images/sponsor/titanSoft.png"
          title="titanSoft"
          alt="titanSoft"
        />
      </a>
      <a
        href="https://blockstudio.tw/"
        class="block bg-white p-20px rounded-16px max-w-250px mx-auto mt-24px md:mt-0 md:ml-20px"
      >
        <img
          class="w-full"
          src="@/assets/images/sponsor/blockStudio.png"
          title="blockStudio"
          alt="blockStudio"
        />
      </a>
    </div>
  </section>
</template>

<style lang="scss">
@media (min-width: 768px) {
  .sponsorsBlock {
    &__title {
      position: relative;
      &::before,
      &::after {
        display: block;
        position: absolute;
        content: "";
        background-image: url("@/assets/images/sponsor/star.png");
        background-position: center;
        background-size: contain;
        height: 36px;
        width: 36px;
      }

      &::before {
        top: 0;
        left: calc(50% - 184px);
      }
      &::after {
        top: 0;
        left: calc(50% + 148px);
      }
    }
  }
}
</style>
