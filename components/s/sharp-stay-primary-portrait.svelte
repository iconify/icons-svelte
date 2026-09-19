<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi7egzbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-stay-primary-portrait" {...props}></Icon>
<style>
:global(.bi7egzbxv) {
  fill: currentColor;
  d: path("M5.01 1v22H19V1zM17 19H7V5h10z");
}

</style>
