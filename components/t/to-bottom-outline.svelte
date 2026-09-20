<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6lc9g5bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y6lc9g5bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:to-bottom-outline" {...props}></Icon>
