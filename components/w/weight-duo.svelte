<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/djs-1ddrm.css';
import '../../css/j/jfru2eb2v.css';
import '../../css/i/izb9cccdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="djs-1ddrm"/><path class="jfru2eb2v wm-a"/><path class="izb9cccdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:weight-duo" {...props}></Icon>
