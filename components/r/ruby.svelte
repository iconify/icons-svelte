<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inb686g-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="inb686g-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:ruby" {...props}></Icon>
