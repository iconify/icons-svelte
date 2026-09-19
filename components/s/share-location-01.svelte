<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kjf-6mb1d.css';
import '../../css/l/lny61nbxl.css';
import '../../css/c/cokx9_blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kjf-6mb1d"/><path class="lny61nbxl"/><path class="cokx9_blg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:share-location-01" {...props}></Icon>
