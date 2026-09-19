<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="raz7z3b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:todolist" {...props}></Icon>
<style>
:global(.raz7z3b8f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 12.962l11.775 7.149L42.5 5.508m-37 18.644l11.775 7.149L42.5 16.699m-37 18.643l11.775 7.15L42.5 27.889");
}

</style>
