<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghvfd6btu.css';
import '../../css/v/vio9gfbpv.css';
import '../../css/g/gu24prbpy.css';
import '../../css/l/lsudu1uhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ghvfd6btu"/><path class="vio9gfbpv"/><path class="gu24prbpy"/><path class="lsudu1uhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wine-glass" {...props}></Icon>
