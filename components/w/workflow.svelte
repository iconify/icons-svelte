<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yrjyowgzc.css';
import '../../css/f/fjkxmjlze.css';
import '../../css/q/qjin-bc2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yrjyowgzc"/><path class="fjkxmjlze"/><path class="qjin-bc2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:workflow" {...props}></Icon>
