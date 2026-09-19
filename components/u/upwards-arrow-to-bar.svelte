<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx4y6cc8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="qx4y6cc8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:upwards-arrow-to-bar" {...props}></Icon>
