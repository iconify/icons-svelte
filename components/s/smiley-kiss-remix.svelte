<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re64yvbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="re64yvbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-kiss-remix" {...props}></Icon>
