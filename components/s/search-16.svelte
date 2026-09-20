<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpirlyb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gpirlyb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:search-16" {...props}></Icon>
