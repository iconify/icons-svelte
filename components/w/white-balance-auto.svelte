<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnj14oqzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnj14oqzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:white-balance-auto" {...props}></Icon>
