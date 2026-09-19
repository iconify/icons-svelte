<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joqi56b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":432};
const content = `<path class="joqi56b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:settings" {...props}></Icon>
