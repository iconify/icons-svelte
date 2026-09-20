<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb0jkwy9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yb0jkwy9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:voice-mail-off-solid" {...props}></Icon>
