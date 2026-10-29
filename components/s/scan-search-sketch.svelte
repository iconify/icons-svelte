<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u-b_b7bce.css';
import '../../css/v/vbr8th6tj.css';
import '../../css/w/wchmfjfsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u-b_b7bce wm-deco"/><path class="vbr8th6tj wm-k"/><path class="wchmfjfsw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-search-sketch" {...props}></Icon>
