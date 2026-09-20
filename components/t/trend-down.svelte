<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7owgib4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p7owgib4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:trend-down" {...props}></Icon>
