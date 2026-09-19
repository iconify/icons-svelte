<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/sxr1bwbgh.css';
import '../../css/n/nkpchpbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect transform="rotate(-10 3.61 36.534)" class="sxr1bwbgh"/><path class="nkpchpbhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:straight-razor" {...props}></Icon>
