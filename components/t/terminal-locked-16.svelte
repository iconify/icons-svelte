<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyk7o8xin.css';
import '../../css/j/j0z--qb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uyk7o8xin"/><path class="j0z--qb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:terminal-locked-16" {...props}></Icon>
