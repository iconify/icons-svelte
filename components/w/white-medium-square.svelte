<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ivo8mmwmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:white-medium-square" {...props}></Icon>
<style>
:global(.ivo8mmwmr) {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M33 30a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3z");
}

</style>
