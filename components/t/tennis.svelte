<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z5s_iw4ay.css';
import '../../css/q/qukbo802n.css';
import '../../css/a/ahh3l923f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z5s_iw4ay"/><path class="qukbo802n"/><path class="ahh3l923f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tennis" {...props}></Icon>
