<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k96n5jw4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k96n5jw4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:star-cancelled" {...props}></Icon>
