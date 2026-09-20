<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpmkb9brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:thermostat-carbon-sharp" {...props}></Icon>
<style>
:global(.hpmkb9brn) {
  fill: currentColor;
  d: path("M12 21.377L2.623 12L12 2.623L21.377 12z");
}

</style>
