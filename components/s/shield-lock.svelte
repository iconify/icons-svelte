<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j2vbli9go.css';
import '../../css/b/b08rucc_a.css';
import '../../css/p/p2yzh8egz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j2vbli9go"/><path class="b08rucc_a"/><path class="p2yzh8egz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-lock" {...props}></Icon>
