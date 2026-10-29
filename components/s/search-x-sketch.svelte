<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vzu_nabrz.css';
import '../../css/t/ttwf-zbzb.css';
import '../../css/l/lzc_04b6m.css';
import '../../css/o/on-fg_sbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vzu_nabrz"/><path class="ttwf-zbzb wm-a"/><path class="lzc_04b6m wm-k"/><path class="on-fg_sbj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:search-x-sketch" {...props}></Icon>
