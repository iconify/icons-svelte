<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<circle class="eigjrvbls"/><path class="ee40l2yib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:storyblocks-icon" {...props}></Icon>
<style>
:global(.ee40l2yib) {
  d: path("M122.4 60.8v86.4c-24 0-43.2-19.2-43.2-43.2s19.2-43.2 43.2-43.2m11.2 134.4v-86.4c24 0 43.2 19.2 43.2 43.2c0 23.613-18.586 42.58-42.043 43.185zM154 60.8c11.2 0 20.4 9.2 20.4 20.4s-9.2 20.4-20.4 20.4s-20.4-9.2-20.4-20.4s9.2-20.4 20.4-20.4m-52 93.6c11.2 0 20.4 9.2 20.4 20.4s-9.2 20.4-20.4 20.4s-20.4-9.2-20.4-20.4s9.2-20.4 20.4-20.4");
}

:global(.eigjrvbls) {
  cx: 128px;
  cy: 128px;
  r: 128px;
  fill: var(--svg-color--ffe121, #ffe121);
}

</style>
