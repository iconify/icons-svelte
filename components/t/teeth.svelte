<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxwa2fbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="jxwa2fbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:teeth" {...props}></Icon>
