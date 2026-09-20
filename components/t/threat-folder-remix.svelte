<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5_n65d2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j5_n65d2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:threat-folder-remix" {...props}></Icon>
