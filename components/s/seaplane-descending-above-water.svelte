<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3793b6te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p3793b6te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane-descending-above-water" {...props}></Icon>
