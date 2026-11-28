<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n3uwabccu.css';
import '../../css/z/ztli_d_ek.css';
import '../../css/m/mckmxfhkw.css';
import '../../css/q/quh1t-ouf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n3uwabccu"/><path class="ztli_d_ek"/><path class="mckmxfhkw"/><path class="quh1t-ouf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:screen-share" {...props}></Icon>
