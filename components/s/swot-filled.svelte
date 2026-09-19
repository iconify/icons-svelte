<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edd34ccwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="edd34ccwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:swot-filled" {...props}></Icon>
