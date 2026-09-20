<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z05vgab-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stream-apps-sharp" {...props}></Icon>
<style>
:global(.z05vgab-j) {
  fill: currentColor;
  d: path("M14.116 16.173v-7.48h7.653v6h-6.173zM6 22V2h12v4.923h-1V5.5H7v13h10v-1.423h1V22z");
}

</style>
