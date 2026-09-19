<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6a31sbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="t6a31sbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:volume-off" {...props}></Icon>
