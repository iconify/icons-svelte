<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwtf473fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwtf473fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scan-text" {...props}></Icon>
