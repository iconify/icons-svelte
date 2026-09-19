<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv2u20usj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mv2u20usj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:stopwatch" {...props}></Icon>
