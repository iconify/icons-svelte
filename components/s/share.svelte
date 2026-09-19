<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtf12vb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rtf12vb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:share" {...props}></Icon>
