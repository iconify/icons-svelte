<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk5g6cc_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:vertical-distribute-sharp" {...props}></Icon>
<style>
:global(.bk5g6cc_t) {
  fill: currentColor;
  d: path("M2 22v-2h20v2zm5-8.5v-3h10v3zM2 4V2h20v2z");
}

</style>
