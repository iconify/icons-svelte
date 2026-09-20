<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vryv1t93k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="vryv1t93k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-12" {...props}></Icon>
