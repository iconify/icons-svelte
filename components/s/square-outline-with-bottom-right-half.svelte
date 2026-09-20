<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2pgsccln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k2pgsccln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:square-outline-with-bottom-right-half" {...props}></Icon>
