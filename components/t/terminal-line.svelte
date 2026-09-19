<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfbaaobvg.css';
import '../../css/v/vejvu3b9p.css';
import '../../css/i/ib8p1do7v.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 yfbaaobvg"/><path class="clr-i-outline clr-i-outline-path-2 vejvu3b9p"/><path class="clr-i-outline clr-i-outline-path-3 ib8p1do7v"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:terminal-line" {...props}></Icon>
