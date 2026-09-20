<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tldjdxb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sweep-outline-sharp" {...props}></Icon>
<style>
:global(.tldjdxb6d) {
  fill: currentColor;
  d: path("M10.5 17.5v-1h5v1zm-4.45-.192l-4.963-4.964l.713-.713l4.25 4.25l9.15-9.15l.714.713zM14.5 13.5v-1h5v1zm4-4v-1h5v1z");
}

</style>
