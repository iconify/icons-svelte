<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tygj4ib7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:work-outline-sharp" {...props}></Icon>
<style>
:global(.tygj4ib7i) {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm2-2h16V8H4zm6-13h4V4h-4zM4 19V8z");
}

</style>
