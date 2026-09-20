<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dvv3v5pfz.css';
import '../../css/o/oh3q4ebdx.css';
import '../../css/q/qdnm17w9y.css';
import '../../css/h/hbiqkm9hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dvv3v5pfz"/><path clip-rule="evenodd" class="oh3q4ebdx"/><path class="qdnm17w9y"/><path class="hbiqkm9hq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-2-bold" {...props}></Icon>
