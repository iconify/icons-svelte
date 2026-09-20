<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o59d3w3ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o59d3w3ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:surface-right-outline" {...props}></Icon>
