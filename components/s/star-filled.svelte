<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0u51cbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c0u51cbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:star-filled" {...props}></Icon>
