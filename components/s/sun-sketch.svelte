<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vsnu5gbhp.css';
import '../../css/j/jlb-a5b-w.css';
import '../../css/x/xtrag_b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vsnu5gbhp"/><path class="jlb-a5b-w wm-k"/><path class="wm-a xtrag_b9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sun-sketch" {...props}></Icon>
