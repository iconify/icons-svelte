<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyfsf1tvs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j2vbli9go.css';
import '../../css/x/xt2qpeb4g.css';
import '../../css/g/gfa_nbc5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyfsf1tvs secondary"/><g class="dt0cm9dhy primary"><path class="j2vbli9go"/><path class="xt2qpeb4g"/><path class="gfa_nbc5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-arrow-right-duo" {...props}></Icon>
