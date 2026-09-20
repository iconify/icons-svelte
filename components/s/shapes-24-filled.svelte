<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivp32xb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:shapes-24-filled" {...props}></Icon>
<style>
:global(.ivp32xb1w) {
  fill: currentColor;
  d: path("M2 8.75A6.75 6.75 0 0 1 15.459 8H12.25A4.25 4.25 0 0 0 8 12.25v3.209A6.75 6.75 0 0 1 2 8.75M12.25 9A3.25 3.25 0 0 0 9 12.25v6.5A3.25 3.25 0 0 0 12.25 22h6.5A3.25 3.25 0 0 0 22 18.75v-6.5A3.25 3.25 0 0 0 18.75 9z");
}

</style>
