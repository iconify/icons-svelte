<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcridmbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcridmbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-off-fill-round" {...props}></Icon>
