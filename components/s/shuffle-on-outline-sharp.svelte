<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd9ru6b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:shuffle-on-outline-sharp" {...props}></Icon>
<style>
:global(.bd9ru6b3l) {
  fill: currentColor;
  d: path("M2 22V2h20v20zm12.23-3H19v-4.712h-1v2.954l-3.477-3.476l-.713.713L17.33 18h-3.1zm-8.522 0L18 6.708v3.004h1V5h-4.77v1h3.062L5 18.292zm3.678-8.925l.689-.688L5.689 5L5 5.689z");
}

</style>
