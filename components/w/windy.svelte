<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ni5hshxsz"/><path class="z7leqybgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:windy" {...props}></Icon>
<style>
:global(.ni5hshxsz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.47 6c-.63 12.26-2 36.06 8 36.06s17-26.43 18-30.33");
}

:global(.z7leqybgy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 6c.57 12.24 3.27 36 13.3 36s19-21.41 20.55-30.33");
}

</style>
