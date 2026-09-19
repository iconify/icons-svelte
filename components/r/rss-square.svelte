<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4j6sacdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="t4j6sacdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:rss-square" {...props}></Icon>
