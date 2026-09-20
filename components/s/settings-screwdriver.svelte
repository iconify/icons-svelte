<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/figruzihz.css';
import '../../css/l/ll5ze5bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="figruzihz"/><path class="ll5ze5bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:settings-screwdriver" {...props}></Icon>
