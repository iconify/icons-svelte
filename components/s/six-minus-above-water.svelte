<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb92sq2ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pb92sq2ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:six-minus-above-water" {...props}></Icon>
