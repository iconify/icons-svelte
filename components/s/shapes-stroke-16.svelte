<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8cdtrbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f8cdtrbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shapes-stroke-16" {...props}></Icon>
