<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9i96qbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="s9i96qbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-1" {...props}></Icon>
