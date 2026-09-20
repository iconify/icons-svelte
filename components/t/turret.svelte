<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="ij968mb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:turret" {...props}></Icon>
<style>
:global(.ij968mb3j) {
  fill: var(--svg-color--195de6, #195de6);
  d: path("m208 288l-16-128h32l16-16V0h-48v48h-32V0H96v48H64V0H16v144l16 16h32L48 288H16L0 304v80h256v-80l-16-16z");
}

</style>
