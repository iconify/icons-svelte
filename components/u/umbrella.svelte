<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wqig7lvne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:umbrella" {...props}></Icon>
<style>
:global(.wqig7lvne) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.806 40.838a3.097 3.097 0 0 0 6.194 0V23.565m-19.5 0a19.5 19.5 0 0 1 39 0a4.875 4.875 0 1 0-9.75 0a4.875 4.875 0 1 0-9.75 0a4.875 4.875 0 1 0-9.75 0a4.875 4.875 0 1 0-9.75 0");
}

</style>
