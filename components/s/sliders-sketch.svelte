<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vzbtg_b3k.css';
import '../../css/d/d8zqsacyg.css';
import '../../css/q/q_g5f4r3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vzbtg_b3k wm-k"/><path class="d8zqsacyg wm-k"/><path class="q_g5f4r3u wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sliders-sketch" {...props}></Icon>
