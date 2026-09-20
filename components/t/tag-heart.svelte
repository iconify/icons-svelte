<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcm41yf7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcm41yf7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-heart" {...props}></Icon>
