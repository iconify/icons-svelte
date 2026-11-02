<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qczb0h48q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qczb0h48q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rss-2-fill" {...props}></Icon>
