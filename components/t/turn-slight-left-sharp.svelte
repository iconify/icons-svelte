<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kklm6bb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:turn-slight-left-sharp" {...props}></Icon>
<style>
:global(.kklm6bb6k) {
  fill: currentColor;
  d: path("M13.5 19.77v-7.312l-5.788-5.77V9.67h-1V5h4.669v1H8.4l6.1 6.08v7.69z");
}

</style>
