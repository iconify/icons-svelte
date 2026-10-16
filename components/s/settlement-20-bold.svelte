<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptizy_zew.css';
import '../../css/u/u-8r7_bwc.css';
import '../../css/u/usgixfbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ptizy_zew"/><path class="u-8r7_bwc"/><path class="usgixfbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:settlement-20-bold" {...props}></Icon>
