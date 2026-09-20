<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/h/hhc5iou_j.css';
import '../../css/w/ws_62zb9c.css';
import '../../css/u/u5aegb-hj.css';
import '../../css/e/euhwhnbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="hhc5iou_j"/><path class="ws_62zb9c"/><path class="u5aegb-hj"/><path class="euhwhnbwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-line-line-duotone" {...props}></Icon>
