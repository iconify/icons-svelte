<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmy-ii47q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xmy-ii47q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:wifi-abnormal-outline" {...props}></Icon>
