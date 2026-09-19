<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6b_6wars.css';
import '../../css/i/iabrmvfcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h6b_6wars"/><path class="iabrmvfcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-layer" {...props}></Icon>
