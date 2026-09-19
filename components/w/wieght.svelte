<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbm03u4xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="kbm03u4xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:wieght" {...props}></Icon>
