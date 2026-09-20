<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlw2svjrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="tlw2svjrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-4" {...props}></Icon>
