<template>
  <header class="shadow w-screen">
    <nav>
      <nav class="flex items-center justify-between flex-wrap bg-green-400 p-6">
        <div class="flex items-center flex-shrink-0 text-white mr-6">
          <moro-icon class="pr-1 w-10" />
          <span class="font-semibold text-xl tracking-tight">PlatziExchange</span>
        </div>
        <div class="hidden sm:block w-full blok flex-grow lg:flex lg:items-center lg:wauto">
          <div class="text-sm lg:flex-grow"></div>
        </div>
      </nav>
    </nav>
  </header>
</template>

<script>
import moroIcon from '@/components/moroIcon'

export default {
  name: 'moroIcon',
  components: {
    moroIcon 
  }
}
</script>