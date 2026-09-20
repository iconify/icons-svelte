<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kjzly26zd.css';
import '../../css/u/u-th1gbxa.css';
import '../../css/o/o4kr9t73l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kjzly26zd"/><path class="u-th1gbxa"/><path class="o4kr9t73l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:toggle-on-sharp-two-tone" {...props}></Icon>
