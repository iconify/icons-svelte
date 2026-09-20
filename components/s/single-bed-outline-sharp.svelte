<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya9d7nbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:single-bed-outline-sharp" {...props}></Icon>
<style>
:global(.ya9d7nbcp) {
  fill: currentColor;
  d: path("M6.77 18h-.54l-.38-2H5v-5h2V7h10v4h2v5h-.85l-.38 2h-.54l-.38-2h-9.7zm5.73-7H16V8h-3.5zM8 11h3.5V8H8zm-2 4h12v-3H6zm12 0H6z");
}

</style>
