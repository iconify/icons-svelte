<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf5yykb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf5yykb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:statamic" {...props}></Icon>
