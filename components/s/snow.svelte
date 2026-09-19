<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k37_r3b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="k37_r3b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:snow" {...props}></Icon>
