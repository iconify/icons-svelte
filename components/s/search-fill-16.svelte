<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w__re01gs.css';
import '../../css/c/ctx28g1ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="w__re01gs"/><path class="ctx28g1ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:search-fill-16" {...props}></Icon>
