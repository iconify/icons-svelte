<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/rz75sybsq.css';
import '../../css/h/hbry40bnh.css';
import '../../css/x/xto-uckdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="rz75sybsq"/><path class="hbry40bnh"/><path class="xto-uckdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:security" {...props}></Icon>
