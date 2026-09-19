<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3u1j7bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v3u1j7bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-mode-2" {...props}></Icon>
