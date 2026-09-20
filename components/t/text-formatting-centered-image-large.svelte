<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0xwz2w_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v0xwz2w_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-centered-image-large" {...props}></Icon>
