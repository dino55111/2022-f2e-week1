<script setup></script>

<template>
  <section class="awardsBlock bg-hex-f1ede9 pt-30px pb-60px">
    <h2 class="text-hex-4e7b57 font-900 text-24px md:text-60px">
      <div class="whitespace-nowrap">
        區區修煉已經無法滿足了嗎？還有比賽等著你！
      </div>
    </h2>

    <div class="awardsBlock__leftInfo mt-80px md:mt-60px">
      <div
        class="awardsBlock__dot bg-white rounded-25px max-w-1000px w-[80%] mx-auto p-24px md:w-[50%]"
      >
        <h3 class="text-hex-4e7b57 font-900 text-16px text-center md:text-24px">
          評審機制
        </h3>

        <div class="font-900 text-14px mt-16px md:text-16px">
          初選
          <ul class="font-500">
            <li>將由六角學院前端、UI 評審進行第一波篩選。</li>
          </ul>
        </div>

        <div class="font-900 text-14px mt-16px md:text-16px md:mt-24px">
          決選
          <ul class="font-500">
            <li>
              由六角學院與贊助廠商討論，進行最後篩選，並於 12/30(五)
              由評審進行直播公布名單！
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="awardsBlock__rightInfo mt-80px md:mt-60px">
      <div
        class="awardsBlock__dot bg-white rounded-25px max-w-1000px w-[80%] mx-auto p-24px md:w-[50%]"
      >
        <h3 class="text-hex-4e7b57 font-900 text-16px text-center md:text-24px">
          比賽獎項
        </h3>

        <div
          class="font-500 text-14px mt-16px leading-6 md:leading-6 md:text-16px md:mt-24px"
        >
          <ol>
            <li>1. 初選佳作 共六十位 數位獎狀</li>
            <li>2. 個人企業獎 共六位 NTD 3,000/位</li>
            <li>3. 團體企業獎 共三組 NTD 10,000/組</li>
            <li>4. 以上皆提供完賽數位獎狀</li>
          </ol>
        </div>
      </div>
    </div>

    <div
      class="awardsBlock__dot flex justify-center items-center mt-120px md:mt-80px"
    >
      <button
        class="awardsBlock__button bg-hex-4e7b57 px-60px py-20px rounded-10px text-24px text-white font-900 hover:bg-white hover:text-hex-4e7b57"
      >
        立即報名!
      </button>
    </div>
  </section>
</template>

<style lang="scss">
.awardsBlock {
  &__leftInfo {
    background: linear-gradient(90deg, #4e7b57 50%, transparent 50%);
  }

  &__rightInfo {
    background: linear-gradient(90deg, transparent 50%, #4e7b57 50%);
  }

  &__dot {
    position: relative;
    &::before {
      position: absolute;
      display: block;
      content: "";
      width: 20px;
      height: 20px;
      background-color: white;
      border-radius: 100%;
      top: -40px;
      left: calc(50% - 10px);
    }
  }

  &__button {
    position: relative;
    &::before,
    &::after {
      content: "";
      position: absolute;
      display: block;
      height: 100%;
      width: 10px;
      background-color: #69a575;
      border-radius: 5px;
      top: 0;
    }

    &::before {
      left: -50px;
      transform: rotate(-20deg);
    }

    &::after {
      right: -50px;
      transform: rotate(20deg);
    }
  }
}
</style>
