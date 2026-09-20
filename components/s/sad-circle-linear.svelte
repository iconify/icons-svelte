<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/k/kmnr8jx4o.css';
import '../../css/b/bx61cb_8u.css';
import '../../css/w/wbw_ixbrw.css';
import '../../css/y/yad62e0rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="kmnr8jx4o"/><path class="bx61cb_8u"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sad-circle-linear" {...props}></Icon>
