<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3u4e_bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3u4e_bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:steering-wheel-filled" {...props}></Icon>
