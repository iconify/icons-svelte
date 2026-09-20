<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjarxlb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjarxlb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-security" {...props}></Icon>
