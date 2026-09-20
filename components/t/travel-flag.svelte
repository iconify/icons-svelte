<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz9x-0blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xz9x-0blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:travel-flag" {...props}></Icon>
