<template>
  <template v-if="displayHideButton">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      height="48"
      width="48"
      viewBox="0 0 48 48"
    >
      <!--  eslint-disable max-len -->
      <path
        d="m40.8 44.8-8.4-8.25q-1.75.7-3.95 1.075T24 38q-7.3 0-13.25-4.075T2 23q1-2.6 2.775-5.075T9.1 13.2L2.8 6.9l2.1-2.15L42.75 42.6ZM24 31.5q.7 0 1.5-.125T26.85 31L16 20.15q-.25.6-.375 1.35-.125.75-.125 1.5 0 3.6 2.5 6.05 2.5 2.45 6 2.45Zm13.9 2-6.45-6.45q.5-.8.775-1.875T32.5 23q0-3.55-2.475-6.025Q27.55 14.5 24 14.5q-1.1 0-2.15.25-1.05.25-1.9.8L14.45 10q1.75-.8 4.475-1.4Q21.65 8 24.25 8q7.15 0 13.075 4.075Q43.25 16.15 46 23q-1.3 3.2-3.35 5.85-2.05 2.65-4.75 4.65Zm-8.65-8.65-7.1-7.1q1.45-.55 3-.225 1.55.325 2.7 1.425 1.15 1.15 1.6 2.575.45 1.425-.2 3.325Z"
      />
      <!--  eslint-enable max-len -->
    </svg>
  </template>
  <template v-if="!displayHideButton">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      height="48"
      width="48"
      viewBox="0 0 48 48"
    >
      <!--  eslint-disable max-len -->
      <path
        d="M24 31.5q3.55 0 6.025-2.475Q32.5 26.55 32.5 23q0-3.55-2.475-6.025Q27.55 14.5 24 14.5q-3.55 0-6.025 2.475Q15.5 19.45 15.5 23q0 3.55 2.475 6.025Q20.45 31.5 24 31.5Zm0-2.9q-2.35 0-3.975-1.625T18.4 23q0-2.35 1.625-3.975T24 17.4q2.35 0 3.975 1.625T29.6 23q0 2.35-1.625 3.975T24 28.6Zm0 9.4q-7.3 0-13.2-4.15Q4.9 29.7 2 23q2.9-6.7 8.8-10.85Q16.7 8 24 8q7.3 0 13.2 4.15Q43.1 16.3 46 23q-2.9 6.7-8.8 10.85Q31.3 38 24 38Z"
      />
      <!--  eslint-enable max-len -->
    </svg>
  </template>
</template>

<script>
export default {
  name: 'HideOrShowIcon',
  props: {
    displayHideButton: {
      type: Boolean,
      required: true
    }
  }
};
</script>

<style scoped>
svg {
  width: 20px;
  height: 20px;
  fill: white;
}
</style>
