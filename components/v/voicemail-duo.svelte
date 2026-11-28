<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns8e344ry.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/szn6eo7_q.css';
import '../../css/g/gg1-q2dfk.css';
import '../../css/t/t-dm3oq4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns8e344ry secondary"/><g class="dt0cm9dhy primary"><path class="szn6eo7_q"/><path class="gg1-q2dfk"/><path class="t-dm3oq4k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:voicemail-duo" {...props}></Icon>
