<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amb5sjbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="amb5sjbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:window-close-o" {...props}></Icon>
