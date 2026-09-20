<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbukqtlin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stack-group-sharp" {...props}></Icon>
<style>
:global(.bbukqtlin) {
  fill: currentColor;
  d: path("M9 21v-6H3V3h12v6h6v12z");
}

</style>
