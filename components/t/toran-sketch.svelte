<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rqhbxpmil.css';
import '../../css/s/sd6unnbbl.css';
import '../../css/f/f7sc4du7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rqhbxpmil"/><path class="sd6unnbbl wm-k"/><path class="f7sc4du7o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:toran-sketch" {...props}></Icon>
