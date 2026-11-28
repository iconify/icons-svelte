<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_ahlubpw.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zrjey1bzk.css';
import '../../css/h/hv2uvbznp.css';
import '../../css/n/n4_kssl7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u_ahlubpw"/><g class="dt0cm9dhy primary"><path class="zrjey1bzk"/><path class="hv2uvbznp"/><path class="n4_kssl7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:semicolon-duo" {...props}></Icon>
