<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l94p16b8n.css';
import '../../css/p/pdn-wtbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="l94p16b8n"/><path class="pdn-wtbcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:search-1" {...props}></Icon>
