<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhbal1bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stack-off-sharp" {...props}></Icon>
<style>
:global(.yhbal1bbq) {
  fill: currentColor;
  d: path("M21 18.189L11.812 9H21zM14 6.616V4H6.812l-1-1H15v3.616zm6.287 15.098L19.573 21H9V10.427l-5-5V14h2.616v1H3V4.427l-.713-.713L3 3l18 18z");
}

</style>
