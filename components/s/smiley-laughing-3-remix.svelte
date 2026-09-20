<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxng5pzer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gxng5pzer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-laughing-3-remix" {...props}></Icon>
