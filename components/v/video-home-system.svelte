<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrrjxl14w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrrjxl14w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-home-system" {...props}></Icon>
