<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/rlnnxobai.css';
import '../../css/i/i2ddy7fru.css';
import '../../css/u/u3gfgccil.css';
import '../../css/w/w47x50q8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="rlnnxobai wm-deco"/><path class="i2ddy7fru wm-deco"/><path class="u3gfgccil"/><path class="w47x50q8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trending-down-blueprint" {...props}></Icon>
