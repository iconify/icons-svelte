<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ropndeb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ropndeb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:sort-down" {...props}></Icon>
