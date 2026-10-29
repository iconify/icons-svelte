<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f3r-8yyut.css';
import '../../css/a/att42bbkg.css';
import '../../css/j/j_vnhybnm.css';
import '../../css/r/rri6uechc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f3r-8yyut"/><path class="att42bbkg wm-shadow"/><path class="j_vnhybnm"/><path class="rri6uechc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thandai-engrave" {...props}></Icon>
