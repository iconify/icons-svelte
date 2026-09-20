<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeg4hwboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:turn-slight-right-sharp" {...props}></Icon>
<style>
:global(.jeg4hwboi) {
  fill: currentColor;
  d: path("M9.5 19.77v-7.69L15.6 6h-2.98V5h4.669v4.67h-1V6.688l-5.789 5.77v7.311z");
}

</style>
