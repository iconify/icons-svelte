<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2b_tlbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h2b_tlbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:sleep" {...props}></Icon>
