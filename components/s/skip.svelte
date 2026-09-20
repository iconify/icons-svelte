<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2htacc8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2htacc8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:skip" {...props}></Icon>
