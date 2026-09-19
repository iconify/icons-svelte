<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icxlooygs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-navigation" {...props}></Icon>
<style>
:global(.icxlooygs) {
  fill: currentColor;
  d: path("M12 2L4.5 20.29l.71.71L12 18l6.79 3l.71-.71z");
}

</style>
