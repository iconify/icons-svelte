<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ay0wbtbik"/><path class="e5okk4urv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sling" {...props}></Icon>
<style>
:global(.ay0wbtbik) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.642 43.5l-8.521-21.468h6.613L26.255 43.5zm8.716-39l8.521 21.468h-6.613L21.745 4.5z");
}

:global(.e5okk4urv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.619 15.234L21.995 32.766h-6.614l10.624-17.532zM19.642 43.5l10.624-17.532M26.255 43.5l10.624-17.532m-25.737-3.936L21.766 4.5m-4.032 17.532L28.358 4.5");
}

</style>
