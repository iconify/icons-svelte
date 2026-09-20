<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkzmbib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xkzmbib4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:weight-fill" {...props}></Icon>
