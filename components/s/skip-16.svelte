<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvc7fdb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uvc7fdb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:skip-16" {...props}></Icon>
