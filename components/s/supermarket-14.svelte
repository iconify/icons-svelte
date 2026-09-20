<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lywattbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lywattbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:supermarket-14" {...props}></Icon>
