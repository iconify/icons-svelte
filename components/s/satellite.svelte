<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2cfx4_um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2cfx4_um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:satellite" {...props}></Icon>
