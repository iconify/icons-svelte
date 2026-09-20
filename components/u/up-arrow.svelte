<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mbcy0dnue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:up-arrow" {...props}></Icon>
<style>
:global(.mbcy0dnue) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("m64 22.95l31.13 42.47H75.71v39.63H52.48V65.42H32.86z");
}

</style>
