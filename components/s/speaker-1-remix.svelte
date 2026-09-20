<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy6cmybio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wy6cmybio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:speaker-1-remix" {...props}></Icon>
