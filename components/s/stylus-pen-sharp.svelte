<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izvtx9biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stylus-pen-sharp" {...props}></Icon>
<style>
:global(.izvtx9biz) {
  fill: currentColor;
  d: path("m6 16l2.5-9H10V5.5L11.5 2h1L14 5.5V7h1.5l2.5 9zm-2 5l1-3h14l1 3z");
}

</style>
