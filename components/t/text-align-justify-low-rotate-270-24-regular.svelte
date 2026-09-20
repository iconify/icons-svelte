<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv1qrt1bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-justify-low-rotate-270-24-regular" {...props}></Icon>
<style>
:global(.iv1qrt1bo) {
  fill: currentColor;
  d: path("M5.75 11a.75.75 0 0 1-.75-.75v-7.5a.75.75 0 0 1 1.5 0v7.5a.75.75 0 0 1-.75.75m13 11a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v18.5a.75.75 0 0 1-.75.75M11.5 10.25a.75.75 0 0 0 1.5 0v-7.5a.75.75 0 0 0-1.5 0z");
}

</style>
