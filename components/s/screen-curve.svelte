<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voc__pi4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="voc__pi4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screen-curve" {...props}></Icon>
