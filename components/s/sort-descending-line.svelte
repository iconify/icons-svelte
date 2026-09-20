<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg2i99t7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg2i99t7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sort-descending-line" {...props}></Icon>
