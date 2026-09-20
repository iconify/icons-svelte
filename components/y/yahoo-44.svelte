<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mro705bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="mro705bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-44" {...props}></Icon>
