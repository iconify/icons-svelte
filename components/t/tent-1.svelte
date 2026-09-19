<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xocd9kbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="xocd9kbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:tent-1" {...props}></Icon>
