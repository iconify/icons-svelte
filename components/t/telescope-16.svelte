<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkwmo2b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zkwmo2b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:telescope-16" {...props}></Icon>
