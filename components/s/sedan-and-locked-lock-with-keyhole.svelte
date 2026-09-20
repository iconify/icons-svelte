<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa2ykobom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wa2ykobom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sedan-and-locked-lock-with-keyhole" {...props}></Icon>
