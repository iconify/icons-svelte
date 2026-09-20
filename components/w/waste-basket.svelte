<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riqzryb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="riqzryb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:waste-basket" {...props}></Icon>
