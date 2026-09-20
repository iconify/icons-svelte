<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhtronb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hhtronb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:send-email-remix" {...props}></Icon>
