<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhpbuwbuk.css';
import '../../css/o/o8nz3vbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hhpbuwbuk"/><path class="o8nz3vbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wrench" {...props}></Icon>
