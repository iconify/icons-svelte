<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7v0rzbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y7v0rzbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:view-off-filled" {...props}></Icon>
