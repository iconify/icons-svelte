<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijn9zot8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijn9zot8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:web-plus" {...props}></Icon>
