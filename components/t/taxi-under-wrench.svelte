<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0g1-0_hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c0g1-0_hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:taxi-under-wrench" {...props}></Icon>
