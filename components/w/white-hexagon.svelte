<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0nrgzb4b.css';
import '../../css/j/j4wwoicdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="b0nrgzb4b"/><path class="j4wwoicdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-hexagon" {...props}></Icon>
