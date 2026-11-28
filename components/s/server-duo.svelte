<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dta1u_c9n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pfbjbebmh.css';
import '../../css/s/s6wi2fiqk.css';
import '../../css/c/cdgxmnxdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dta1u_c9n secondary"/><g class="dt0cm9dhy primary"><path class="pfbjbebmh"/><path class="s6wi2fiqk"/><path class="cdgxmnxdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:server-duo" {...props}></Icon>
