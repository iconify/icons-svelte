<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0b5pxbkr.css';
import '../../css/e/ep0q_pklm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j0b5pxbkr"/><path class="ep0q_pklm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scope-2-48" {...props}></Icon>
