<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-xcb-l_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-xcb-l_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-tv-and-phone" {...props}></Icon>
