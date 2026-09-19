<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yss197btb.css';
import '../../css/i/iabrmvfcy.css';
import '../../css/c/c5gmrlmbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yss197btb"/><path class="iabrmvfcy"/><path class="c5gmrlmbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-globe-alt" {...props}></Icon>
