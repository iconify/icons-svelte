<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1h1whk8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sensor-door" {...props}></Icon>
<style>
:global(.h1h1whk8f) {
  fill: currentColor;
  d: path("M4 22V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v18zm11.5-8.5q.625 0 1.063-.437T17 12t-.437-1.062T15.5 10.5t-1.062.438T14 12t.438 1.063t1.062.437");
}

</style>
