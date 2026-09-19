<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g66re9w6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="g66re9w6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square-four" {...props}></Icon>
