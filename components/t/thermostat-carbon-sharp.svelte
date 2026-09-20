<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7udfjbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:thermostat-carbon-sharp" {...props}></Icon>
<style>
:global(.k7udfjbos) {
  fill: currentColor;
  d: path("M12 22.8L1.2 12L12 1.2L22.8 12z");
}

</style>
