<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p0ecc5dsq.css';
import '../../css/a/aw5n4pain.css';
import '../../css/f/fuha1vbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="p0ecc5dsq"/><path class="aw5n4pain"/><path class="fuha1vbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:square-3-stack-3d-20-solid" {...props}></Icon>
