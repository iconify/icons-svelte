<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mtv0-bc_o.css';
import '../../css/m/mit9yg-2j.css';
import '../../css/p/pg9_vdbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mtv0-bc_o"/><path class="mit9yg-2j wm-a"/><path class="pg9_vdbco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:share-2-duo" {...props}></Icon>
