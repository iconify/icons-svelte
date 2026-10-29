<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s89kpjsxi.css';
import '../../css/q/q2s6zvbuh.css';
import '../../css/p/p51kjbcdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s89kpjsxi"/><path class="q2s6zvbuh wm-shadow"/><path class="p51kjbcdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-round-engrave" {...props}></Icon>
