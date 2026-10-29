<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xmy71bqag.css';
import '../../css/b/byf_cebpl.css';
import '../../css/d/dhuewpeee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xmy71bqag"/><path class="byf_cebpl wm-a"/><path class="dhuewpeee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skip-forward-duo" {...props}></Icon>
