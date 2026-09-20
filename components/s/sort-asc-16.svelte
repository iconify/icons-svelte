<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn9qg001w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vn9qg001w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-asc-16" {...props}></Icon>
