<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsp6_lb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dsp6_lb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trilium-notes-dark" {...props}></Icon>
