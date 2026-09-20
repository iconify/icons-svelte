<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7oiq0mio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7oiq0mio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:text-summary-ltr" {...props}></Icon>
