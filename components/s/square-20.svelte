<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c961mpvnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c961mpvnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-20" {...props}></Icon>
