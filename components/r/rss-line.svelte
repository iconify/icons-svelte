<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu3ehfb8w.css';
import '../../css/z/zuzxidbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu3ehfb8w"/><path class="zuzxidbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rss-line" {...props}></Icon>
