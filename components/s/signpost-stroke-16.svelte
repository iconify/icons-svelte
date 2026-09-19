<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9khw75hp.css';
import '../../css/x/xaq4gjbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9khw75hp"/><path class="xaq4gjbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:signpost-stroke-16" {...props}></Icon>
