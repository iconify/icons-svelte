<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dm4x1bp9i.css';
import '../../css/y/yy7qddc7s.css';
import '../../css/c/cuunliqrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dm4x1bp9i"/><path class="yy7qddc7s"/><path class="cuunliqrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-clear" {...props}></Icon>
