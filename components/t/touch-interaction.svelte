<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kql266bwv.css';
import '../../css/y/yceptjbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kql266bwv"/><path class="yceptjbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:touch-interaction" {...props}></Icon>
