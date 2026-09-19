<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d63flqyki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="d63flqyki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:search-plus" {...props}></Icon>
