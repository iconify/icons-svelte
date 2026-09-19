<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhgy9cx9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-king-bed" {...props}></Icon>
<style>
:global(.nhgy9cx9j) {
  fill: currentColor;
  d: path("M20 10V5H4v5H2v7h1.33L4 19h1l.67-2h12.67l.66 2h1l.67-2H22v-7zm-9 0H6V7h5zm7 0h-5V7h5z");
}

</style>
