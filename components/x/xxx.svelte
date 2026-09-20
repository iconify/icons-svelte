<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrtqot-tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrtqot-tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:xxx" {...props}></Icon>
