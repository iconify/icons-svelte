<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjsozkb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjsozkb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:teddy-bear-gloss" {...props}></Icon>
