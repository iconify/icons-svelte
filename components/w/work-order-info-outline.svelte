<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe-f4tbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fe-f4tbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-info-outline" {...props}></Icon>
