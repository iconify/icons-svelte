<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0vwqke5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0vwqke5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:virus-off-outline" {...props}></Icon>
