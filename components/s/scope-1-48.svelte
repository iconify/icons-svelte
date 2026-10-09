<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0b5pxbkr.css';
import '../../css/j/jtr7gubri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j0b5pxbkr"/><path class="jtr7gubri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scope-1-48" {...props}></Icon>
