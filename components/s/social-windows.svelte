<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq5hysa4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="uq5hysa4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-windows" {...props}></Icon>
