<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or11ckbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="or11ckbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:safe-pin" {...props}></Icon>
