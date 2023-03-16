<template>
  <div>
    <div class="flex place-content-center bg-gray-bg min-h-screen">
      <div class="card flex justify-center mx-12 mt-12">
        <div class="relative overflow-hidden pt-16">
          <div class="mx-auto max-w-7xl px-6 lg:px-8">
            <div class="relative" aria-hidden="true">
              <div class="absolute -inset-x-20 bottom-0 bg-gradient-to-t from-white pt-[7%]">
                <div class="bg-white-bg">content app test test test</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LayoutBackground',
}
</script>

<style scoped>
.card {
  height: calc(100% - 2rem);
  border: none;
  padding: 2.68rem;
}
</style>

<!-- Add "scoped" attribute to limit CSS to this component only -->
