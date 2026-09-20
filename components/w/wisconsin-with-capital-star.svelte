<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yndpv1bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yndpv1bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wisconsin-with-capital-star" {...props}></Icon>
