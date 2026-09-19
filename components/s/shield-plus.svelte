<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyi5cjxdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="qyi5cjxdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:shield-plus" {...props}></Icon>
