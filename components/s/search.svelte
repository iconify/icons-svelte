<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgl9-i0zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lgl9-i0zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:search" {...props}></Icon>
