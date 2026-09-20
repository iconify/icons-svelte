<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igesznrfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igesznrfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:signal-strength-1" {...props}></Icon>
