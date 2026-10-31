<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/s/sb58ovbjt.css';
import '../../css/b/bxhzprb-v.css';
import '../../css/i/i1b8jmb3o.css';
import '../../css/k/k1bfb_bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="sb58ovbjt wm-shadow"/><path class="bxhzprb-v"/><path class="i1b8jmb3o"/><path class="k1bfb_bgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:trees" {...props}></Icon>
