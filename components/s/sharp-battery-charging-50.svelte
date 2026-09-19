<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkrwuqbos"/><path class="tanht8vcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-charging-50" {...props}></Icon>
<style>
:global(.tanht8vcw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v9.5h2.53L13 7v5.5h2l-.53 1H17z");
}

:global(.wkrwuqbos) {
  fill: currentColor;
  d: path("M14.47 13.5L11 20v-5.5H9l.53-1H7V22h10v-8.5z");
}

</style>
