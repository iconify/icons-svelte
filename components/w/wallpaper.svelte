<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uf5r49box.css';
import '../../css/e/e2i1rhbxz.css';
import '../../css/d/dvzra1brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uf5r49box"/><circle class="e2i1rhbxz"/><path class="dvzra1brn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wallpaper" {...props}></Icon>
