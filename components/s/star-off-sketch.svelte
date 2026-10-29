<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mmqlpiqfo.css';
import '../../css/m/memzlwbyy.css';
import '../../css/b/bvwl46b5l.css';
import '../../css/w/wx0gwswyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mmqlpiqfo wm-k"/><path class="memzlwbyy wm-s"/><path class="bvwl46b5l wm-k"/><path class="wm-s wx0gwswyg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:star-off-sketch" {...props}></Icon>
