<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeagbexds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xeagbexds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-top-image-large" {...props}></Icon>
