<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-uq13bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-uq13bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:snowman" {...props}></Icon>
