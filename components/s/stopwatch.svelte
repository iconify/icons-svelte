<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wix2zkbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wix2zkbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stopwatch" {...props}></Icon>
