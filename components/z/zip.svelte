<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsyg74b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tsyg74b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:zip" {...props}></Icon>
