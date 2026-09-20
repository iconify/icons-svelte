<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2_3kdbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n2_3kdbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-top-and-bottom-image" {...props}></Icon>
