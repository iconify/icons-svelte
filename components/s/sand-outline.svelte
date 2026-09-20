<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4r3vlmiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z4r3vlmiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sand-outline" {...props}></Icon>
