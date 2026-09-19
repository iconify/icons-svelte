<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgcjx1bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zgcjx1bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:video-filled" {...props}></Icon>
