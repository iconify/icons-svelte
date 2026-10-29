<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z66tkfv3t.css';
import '../../css/t/tbhozsb4v.css';
import '../../css/c/ccaydnkju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z66tkfv3t"/><path class="tbhozsb4v wm-k"/><path class="ccaydnkju wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-sketch" {...props}></Icon>
