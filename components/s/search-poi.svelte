<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgeq-v25e.css';
import '../../css/i/iabrmvfcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vgeq-v25e"/><path class="iabrmvfcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-poi" {...props}></Icon>
