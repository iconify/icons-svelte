<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ris974d5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-settings-sharp" {...props}></Icon>
<style>
:global(.ris974d5c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h13v12.5h-13zm13.86 3.99l3.78-2.23l.86-.51v10l-.86-.51l-3.78-2.23l-.86-.51v-3.5z");
}

</style>
