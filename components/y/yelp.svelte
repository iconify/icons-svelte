<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe9w9bcjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oe9w9bcjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:yelp" {...props}></Icon>
