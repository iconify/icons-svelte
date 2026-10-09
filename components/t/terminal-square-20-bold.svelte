<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkpulpb9y.css';
import '../../css/c/cp728ccvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jkpulpb9y"/><path class="cp728ccvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terminal-square-20-bold" {...props}></Icon>
