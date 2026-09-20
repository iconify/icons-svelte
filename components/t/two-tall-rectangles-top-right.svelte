<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzsgnbbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bzsgnbbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-tall-rectangles-top-right" {...props}></Icon>
