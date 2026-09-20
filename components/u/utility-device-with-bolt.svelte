<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0xn476-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t0xn476-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-device-with-bolt" {...props}></Icon>
