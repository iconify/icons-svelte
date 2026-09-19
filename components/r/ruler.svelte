<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trb0p2uxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="trb0p2uxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:ruler" {...props}></Icon>
