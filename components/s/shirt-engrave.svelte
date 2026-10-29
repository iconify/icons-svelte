<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kp3j7tbra.css';
import '../../css/p/pdw9ohb6s.css';
import '../../css/w/w_97-qb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kp3j7tbra"/><path class="pdw9ohb6s wm-shadow"/><path class="w_97-qb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shirt-engrave" {...props}></Icon>
