<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0zrg5ztm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0zrg5ztm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-arrow-up-down" {...props}></Icon>
