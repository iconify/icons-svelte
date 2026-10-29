<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s0rv1cbpy.css';
import '../../css/o/omclqpx8b.css';
import '../../css/t/tmyu-psjc.css';
import '../../css/o/o0pwwr-ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s0rv1cbpy"/><path class="omclqpx8b wm-k"/><path class="tmyu-psjc wm-k"/><path class="o0pwwr-ng wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-user-sketch" {...props}></Icon>
