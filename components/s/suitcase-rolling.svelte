<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqnz8m81q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="mqnz8m81q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:suitcase-rolling" {...props}></Icon>
