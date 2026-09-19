<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n702l_a5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1229,"height":677};
const content = `<path class="n702l_a5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:tabezou" {...props}></Icon>
