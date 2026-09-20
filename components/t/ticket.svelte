<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an_vu3bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="an_vu3bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:ticket" {...props}></Icon>
