<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/veen_8bxc.css';
import '../../css/q/q8pfntl8k.css';
import '../../css/u/u4-339brq.css';
import '../../css/t/t-i6f8bdi.css';
import '../../css/z/zybwzifyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="veen_8bxc"/><path class="q8pfntl8k wm-k"/><path class="u4-339brq wm-a"/><path class="t-i6f8bdi wm-k"/><path class="wm-a zybwzifyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:warehouse-sketch" {...props}></Icon>
