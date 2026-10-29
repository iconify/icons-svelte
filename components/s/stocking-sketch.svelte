<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a-k3z2s9a.css';
import '../../css/i/ifxccrbkd.css';
import '../../css/x/xsm6pfbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a-k3z2s9a"/><path class="ifxccrbkd wm-k"/><path class="wm-a xsm6pfbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stocking-sketch" {...props}></Icon>
