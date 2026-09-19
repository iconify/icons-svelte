<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i6el-ub2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vocaloid-collection" {...props}></Icon>
<style>
:global(.i6el-ub2l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.632 17.988l21.824 12V17.963l10.912 6.034l-10.912 5.99V42.01L7.632 29.987v12.024l10.912-5.958l-10.912-6.065v-24l10.912 6.035z");
}

</style>
