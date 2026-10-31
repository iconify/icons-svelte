<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy0lobbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy0lobbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:star-off-round" {...props}></Icon>
