<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwi_xactj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwi_xactj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wallbox-round" {...props}></Icon>
