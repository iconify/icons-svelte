<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psp5wabgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="psp5wabgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:swc" {...props}></Icon>
