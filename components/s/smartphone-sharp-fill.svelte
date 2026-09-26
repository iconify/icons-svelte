<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr6h3sp4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-sharp-fill" {...props}></Icon>
<style>
:global(.pr6h3sp4c) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 22C20 22.5523 19.5523 23 19 23L5 23C4.4477 23 4 22.5523 4 22L4 2C4 1.4477 4.4477 1 5 1L19 1C19.5523 1 20 1.4477 20 2L20 22ZM9.5 7L14.5 7L14.5 5L9.5 5L9.5 7Z");
}

</style>
