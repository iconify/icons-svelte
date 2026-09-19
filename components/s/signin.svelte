<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep8hqw--r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ep8hqw--r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:signin" {...props}></Icon>
