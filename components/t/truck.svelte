<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnsv-3qvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bnsv-3qvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:truck" {...props}></Icon>
