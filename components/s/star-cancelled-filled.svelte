<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4uuiyb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4uuiyb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:star-cancelled-filled" {...props}></Icon>
