<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyai-pb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1664};
const content = `<path class="zyai-pb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:vine" {...props}></Icon>
