<template>
<div class="absolute
-bottom-64
lg:-bottom-20
flex
flex-col
lg:flex-row
bg-white
gap-y-4
gap-x-12
px-8- pt-8 pb-12
rounded-md
">
<!-- Flex Item #1 -->
<div class="flex flex-col">
    <h3 class="text-xs mb-2 uppercase">IP Address</h3>
    <span class="text-2xl">{{ipContent.address}}</span>
</div>
<!-- Flex Item #2 -->
<div class="flex flex-col">
    <h3 class="text-xs mb-2 uppercase">Location</h3>
    <span class="text-2xl">{{ipContent.state}}</span>
</div>
<!-- Flex Item #3 -->
<div class="flex flex-col">
    <h3 class="text-xs mb-2 uppercase">Timezone</h3>
    <span class="text-2xl">{{ipContent.timezone}}</span>
</div>
<!-- Flex Item #4 -->
<div class="flex flex-col">
    <h3 class="text-xs mb-2 uppercase">ISP</h3>
    <span class="text-2xl">{{ipContent.isp}}</span>
</div>
</div>  
</template>

<script>
export default {
    props: ["ipContent"]
}
</script>
