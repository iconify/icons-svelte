<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vod3zxb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vod3zxb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screen-broadcast-remix" {...props}></Icon>
