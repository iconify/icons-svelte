<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lwe2irtfj.css';
import '../../css/r/r44f4ccwe.css';
import '../../css/m/me8wp88id.css';
import '../../css/j/jumjmi00d.css';
import '../../css/w/wdwbobudd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lwe2irtfj wm-k"/><path class="r44f4ccwe wm-k"/><path class="me8wp88id wm-k"/><path class="jumjmi00d wm-a"/><path class="wdwbobudd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:upload-sketch" {...props}></Icon>
