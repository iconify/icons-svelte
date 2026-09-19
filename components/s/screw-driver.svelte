<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix28ohbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ix28ohbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:screw-driver" {...props}></Icon>
