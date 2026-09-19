<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k3by9y91o.css';
import '../../css/p/pdn-wtbcg.css';
import '../../css/b/bdnkignkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="k3by9y91o"/><path class="pdn-wtbcg"/><path class="bdnkignkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:search-1-tint" {...props}></Icon>
