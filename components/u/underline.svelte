<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtgyo3bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtgyo3bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:underline" {...props}></Icon>
