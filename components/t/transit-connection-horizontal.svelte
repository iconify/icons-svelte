<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb1346bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb1346bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:transit-connection-horizontal" {...props}></Icon>
