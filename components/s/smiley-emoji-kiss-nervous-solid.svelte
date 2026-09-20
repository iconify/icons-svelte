<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgzcs4-ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wgzcs4-ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-emoji-kiss-nervous-solid" {...props}></Icon>
