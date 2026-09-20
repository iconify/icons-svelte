<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc91lmb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:south-outline-sharp" {...props}></Icon>
<style>
:global(.hc91lmb8b) {
  fill: currentColor;
  d: path("m12 21l-6.346-6.346l.688-.688l5.158 5.151V2.981h1v16.117l5.158-5.157l.688.713z");
}

</style>
