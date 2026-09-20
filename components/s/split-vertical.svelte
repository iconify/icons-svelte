<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz1j1t8jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xz1j1t8jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:split-vertical" {...props}></Icon>
