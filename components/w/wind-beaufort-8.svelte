<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azb25zw4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="azb25zw4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-8" {...props}></Icon>
