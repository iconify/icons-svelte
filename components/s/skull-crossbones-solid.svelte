<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpymo9b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xpymo9b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:skull-crossbones-solid" {...props}></Icon>
