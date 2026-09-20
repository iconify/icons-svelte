<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4z340b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j4z340b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:skull-1-remix" {...props}></Icon>
