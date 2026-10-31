<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkcjm9blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkcjm9blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rss-fill-round" {...props}></Icon>
