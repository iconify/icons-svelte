<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-bfccc7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-bfccc7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trend-upward" {...props}></Icon>
