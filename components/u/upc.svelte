<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntmtzewba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ntmtzewba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:upc" {...props}></Icon>
