<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swka3acgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="swka3acgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:taxi-checkerboard" {...props}></Icon>
