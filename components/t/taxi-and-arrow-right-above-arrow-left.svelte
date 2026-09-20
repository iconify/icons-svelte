<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vro6cvbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vro6cvbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:taxi-and-arrow-right-above-arrow-left" {...props}></Icon>
