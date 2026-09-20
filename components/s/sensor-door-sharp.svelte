<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6s31g2vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sensor-door-sharp" {...props}></Icon>
<style>
:global(.t6s31g2vi) {
  fill: currentColor;
  d: path("M4 22V2h16v20zm11.5-8.5q.625 0 1.063-.437T17 12t-.437-1.062T15.5 10.5t-1.062.438T14 12t.438 1.063t1.062.437");
}

</style>
