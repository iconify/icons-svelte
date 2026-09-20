<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rccltgwpt.css';
import '../../css/b/bg4qdp5ho.css';
import '../../css/o/o-2211bzh.css';
import '../../css/v/vg5zmbblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rccltgwpt"/><path class="bg4qdp5ho"/><path class="o-2211bzh"/><path class="vg5zmbblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sando" {...props}></Icon>
