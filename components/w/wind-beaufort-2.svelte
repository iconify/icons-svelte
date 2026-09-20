<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeg_jyl6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="xeg_jyl6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-2" {...props}></Icon>
