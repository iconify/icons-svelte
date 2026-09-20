<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wycvh4b1h.css';
import '../../css/h/hnh9ojyty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wycvh4b1h"/><path class="hnh9ojyty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-medium-small-square" {...props}></Icon>
