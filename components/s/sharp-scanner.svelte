<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntt3ssblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-scanner" {...props}></Icon>
<style>
:global(.ntt3ssblb) {
  fill: currentColor;
  d: path("m4.2 5l-.7 1.9L17.6 12H3v8h18v-8.86zM7 17H5v-2h2zm12 0H9v-2h10z");
}

</style>
