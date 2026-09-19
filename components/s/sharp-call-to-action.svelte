<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbx506bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-call-to-action" {...props}></Icon>
<style>
:global(.gbx506bbh) {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 16H3v-3h18z");
}

</style>
