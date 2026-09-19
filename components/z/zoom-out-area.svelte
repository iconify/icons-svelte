<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivkxfbb3l.css';
import '../../css/q/qmvfbubxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ivkxfbb3l"/><path class="qmvfbubxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-out-area" {...props}></Icon>
