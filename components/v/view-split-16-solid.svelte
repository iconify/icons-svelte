<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7pxlvmcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n7pxlvmcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:view-split-16-solid" {...props}></Icon>
