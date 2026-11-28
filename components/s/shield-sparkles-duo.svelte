<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad7le-5la.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j2vbli9go.css';
import '../../css/y/yhc39k2dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad7le-5la secondary"/><g class="dt0cm9dhy primary"><path class="j2vbli9go"/><path class="yhc39k2dy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-sparkles-duo" {...props}></Icon>
