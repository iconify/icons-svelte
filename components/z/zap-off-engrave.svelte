<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ccyqkhomb.css';
import '../../css/i/i64imcqzx.css';
import '../../css/m/m9qb4nitn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ccyqkhomb"/><path class="i64imcqzx wm-shadow"/><path class="m9qb4nitn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-off-engrave" {...props}></Icon>
