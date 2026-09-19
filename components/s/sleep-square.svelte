<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-8f7s1ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="y-8f7s1ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sleep-square" {...props}></Icon>
