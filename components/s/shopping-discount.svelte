<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_y1646an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f_y1646an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-discount" {...props}></Icon>
