<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr_en4evr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vr_en4evr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-justified" {...props}></Icon>
