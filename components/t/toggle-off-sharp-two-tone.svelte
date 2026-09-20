<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kjzly26zd.css';
import '../../css/u/u-th1gbxa.css';
import '../../css/e/ep3aj1k1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kjzly26zd"/><path class="u-th1gbxa"/><path class="ep3aj1k1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:toggle-off-sharp-two-tone" {...props}></Icon>
