<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x38s-hs_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-alt-1-bar-outline-rounded" {...props}></Icon>
<style>
:global(.x38s-hs_i) {
  fill: currentColor;
  d: path("M5.438 19.563Q5 19.125 5 18.5v-3q0-.625.438-1.062T6.5 14t1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20t-1.062-.437");
}

</style>
