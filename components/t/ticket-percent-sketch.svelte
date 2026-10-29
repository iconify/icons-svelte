<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q3qqgjbjv.css';
import '../../css/k/k1whg2bmu.css';
import '../../css/u/ukdl6bc-v.css';
import '../../css/h/hp6ffyubb.css';
import '../../css/p/pbkajhwji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q3qqgjbjv"/><path class="k1whg2bmu wm-k"/><path class="ukdl6bc-v wm-a"/><path class="hp6ffyubb wm-k"/><path class="pbkajhwji wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ticket-percent-sketch" {...props}></Icon>
