<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rld3_rbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rld3_rbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:send-variant-clock-outline" {...props}></Icon>
