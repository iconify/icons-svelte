<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m5hvigbmi.css';
import '../../css/w/wjcm_kp5a.css';
import '../../css/e/ekmlpmtjg.css';
import '../../css/c/cgi6aebyp.css';
import '../../css/j/jes-ovvpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m5hvigbmi"/><path class="wjcm_kp5a wm-s"/><path class="ekmlpmtjg wm-s"/><path class="cgi6aebyp"/><path class="jes-ovvpz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:server-cog-duo" {...props}></Icon>
