<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0_t3qb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-pause-outline" {...props}></Icon>
<style>
:global(.d0_t3qb1t) {
  fill: currentColor;
  d: path("M2 22L22 2v11h-2V6.825L6.825 20H13v2zm13 0v-7h2v7zm4 0v-7h2v7zm-5.575-8.6");
}

</style>
