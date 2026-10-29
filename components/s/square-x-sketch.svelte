<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j6iui7arm.css';
import '../../css/g/gduuvtb0e.css';
import '../../css/g/gq17tp1nx.css';
import '../../css/k/k0r6jz3zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j6iui7arm"/><path class="gduuvtb0e wm-k"/><path class="gq17tp1nx wm-a"/><path class="k0r6jz3zq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-x-sketch" {...props}></Icon>
