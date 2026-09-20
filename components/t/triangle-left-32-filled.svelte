<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="guzclhb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-left-32-filled" {...props}></Icon>
<style>
:global(.guzclhb9z) {
  fill: currentColor;
  d: path("M4.682 13.15c-2.242 1.236-2.243 4.457-.001 5.693l19.498 10.75c2.166 1.194 4.82-.373 4.82-2.846V5.255c0-2.473-2.653-4.04-4.819-2.847z");
}

</style>
