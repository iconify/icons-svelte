<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tow-1j04m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tow-1j04m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-end-text" {...props}></Icon>
