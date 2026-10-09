<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs9-ycc5u.css';
import '../../css/j/j9e98_wlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs9-ycc5u"/><path class="j9e98_wlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ticket-20" {...props}></Icon>
