<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hj_0v-x_x.css';
import '../../css/y/y6n7t0e6l.css';
import '../../css/y/y-zlk6bab.css';
import '../../css/z/z60dfsb9q.css';
import '../../css/y/yrtbu4sby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hj_0v-x_x"/><path class="wm-k y6n7t0e6l"/><path class="wm-k y-zlk6bab"/><path class="wm-a z60dfsb9q"/><path class="wm-a yrtbu4sby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skip-back-sketch" {...props}></Icon>
