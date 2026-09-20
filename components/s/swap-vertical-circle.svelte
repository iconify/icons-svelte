<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqjd73bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqjd73bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:swap-vertical-circle" {...props}></Icon>
