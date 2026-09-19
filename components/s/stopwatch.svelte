<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9c09xb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t9c09xb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:stopwatch" {...props}></Icon>
