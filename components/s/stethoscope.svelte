<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmj46q_yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="fmj46q_yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:stethoscope" {...props}></Icon>
