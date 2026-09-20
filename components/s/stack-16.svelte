<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqxwy99bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oqxwy99bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stack-16" {...props}></Icon>
