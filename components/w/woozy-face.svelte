<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl06zb7mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yl06zb7mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:woozy-face" {...props}></Icon>
