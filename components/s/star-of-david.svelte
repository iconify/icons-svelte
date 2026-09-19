<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2k7yobaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":512};
const content = `<path class="t2k7yobaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:star-of-david" {...props}></Icon>
