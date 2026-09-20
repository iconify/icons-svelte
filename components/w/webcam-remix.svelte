<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt9sv002d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mt9sv002d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:webcam-remix" {...props}></Icon>
