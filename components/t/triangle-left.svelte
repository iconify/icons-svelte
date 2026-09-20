<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9hgbnx1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6,"height":16};
const content = `<path class="r9hgbnx1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-left" {...props}></Icon>
