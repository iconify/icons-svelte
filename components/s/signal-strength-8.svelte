<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goppj6bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="goppj6bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:signal-strength-8" {...props}></Icon>
