<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttkz9wikm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ttkz9wikm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:weight-down" {...props}></Icon>
