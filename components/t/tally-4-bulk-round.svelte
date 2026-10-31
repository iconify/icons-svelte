<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzem-_fgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzem-_fgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tally-4-bulk-round" {...props}></Icon>
