<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n557phlxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="n557phlxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:sound" {...props}></Icon>
