<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhpbuwbuk.css';
import '../../css/i/i3i83bc-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hhpbuwbuk"/><path class="i3i83bc-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wrench" {...props}></Icon>
