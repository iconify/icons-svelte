<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srvbhsbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srvbhsbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:size-m" {...props}></Icon>
