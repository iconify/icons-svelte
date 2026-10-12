<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0skfywgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:syntax-highlight-sharp" {...props}></Icon>
<style>
:global(.p0skfywgv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5h7m3.5 0h8M2.75 19h11.5M2.75 9.25h18.5v5.5H2.75zM6.25 12h7");
}

</style>
