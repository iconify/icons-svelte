<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bit21z5fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bit21z5fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:unlock-2" {...props}></Icon>
