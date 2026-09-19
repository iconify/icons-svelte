<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-j4d-1pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z-j4d-1pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:search-sparkle" {...props}></Icon>
