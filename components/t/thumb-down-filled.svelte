<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_p7_hben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f_p7_hben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:thumb-down-filled" {...props}></Icon>
