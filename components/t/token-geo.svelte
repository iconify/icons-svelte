<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flmn98blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="flmn98blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-geo" {...props}></Icon>
