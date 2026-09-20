<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf6-7ubwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yf6-7ubwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:voice-scan-2-remix" {...props}></Icon>
