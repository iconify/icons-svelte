<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-vkctb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r-vkctb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:voice-scan-2-remix" {...props}></Icon>
