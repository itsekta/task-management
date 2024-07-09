<template>
  <div class="banner-section-wrap">
    <div class="banner-section">
      <img
        class="banner-image"
        src="/svg/task-completed.svg"
        alt="task-completed"
      />
      <div class="flex flex-col gap-4 items-center">
        <div class="text-2xl text-center font-semi-bold">
          Task Management and To Do List
        </div>
        <div class="text-center opacity-60">
          This productive tool is designed to help you better manage your task
          convenienntly!
        </div>
      </div>
      <UButton
        icon="i-heroicons-pencil-square"
        color="#5F33E1"
        variant="solid"
        :trailing="true"
        >Let's Start</UButton
      >
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.banner-section-wrap {
  width: 350px;
}
.banner-section {
  display: flex;
  align-items: center;
  flex-direction: column;
  gap: 16px;

  padding: 16px;
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.4);
  border-radius: 16px;
}
.banner-image {
  height: 300px;
  width: 300px;
  margin: 26px 0px;
}
</style>
