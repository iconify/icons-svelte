<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-8d71q8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-8d71q8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rss-2-line" {...props}></Icon>
