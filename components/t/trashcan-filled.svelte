<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up0qlm5zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="up0qlm5zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trashcan-filled" {...props}></Icon>
