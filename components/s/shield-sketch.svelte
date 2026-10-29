<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hbzdspbjk.css';
import '../../css/r/razfpcbqg.css';
import '../../css/w/wjakhsbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hbzdspbjk"/><path class="razfpcbqg"/><path class="wjakhsbqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-sketch" {...props}></Icon>
