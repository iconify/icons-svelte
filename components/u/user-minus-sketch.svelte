<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nsj6ylquj.css';
import '../../css/w/wg5tz-s1o.css';
import '../../css/a/a31ecn6xc.css';
import '../../css/p/p2lfr2uwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nsj6ylquj"/><path class="wg5tz-s1o wm-k"/><path class="a31ecn6xc wm-k"/><path class="p2lfr2uwh wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-minus-sketch" {...props}></Icon>
