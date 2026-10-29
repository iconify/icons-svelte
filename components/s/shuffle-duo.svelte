<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kfg0anbux.css';
import '../../css/x/x0wfh-5ox.css';
import '../../css/l/l0_8r-6fb.css';
import '../../css/y/yakhjr-at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kfg0anbux"/><path class="wm-a x0wfh-5ox"/><path class="l0_8r-6fb"/><path class="wm-a yakhjr-at"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shuffle-duo" {...props}></Icon>
