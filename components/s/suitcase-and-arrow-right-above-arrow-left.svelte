<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew69n7dgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ew69n7dgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:suitcase-and-arrow-right-above-arrow-left" {...props}></Icon>
