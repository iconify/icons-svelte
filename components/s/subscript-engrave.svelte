<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u5fjk2boe.css';
import '../../css/d/d32xvquwx.css';
import '../../css/f/fpn8subxg.css';
import '../../css/x/x-tp0_soj.css';
import '../../css/q/qrlg7vb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u5fjk2boe wm-k"/><path class="d32xvquwx wm-a"/><path class="fpn8subxg wm-shadow"/><path class="wm-k x-tp0_soj"/><path class="qrlg7vb3j wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:subscript-engrave" {...props}></Icon>
