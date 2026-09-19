<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn6x4mbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vn6x4mbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:telephone-x-fill" {...props}></Icon>
