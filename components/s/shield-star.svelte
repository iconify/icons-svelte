<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9qqv3b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l9qqv3b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:shield-star" {...props}></Icon>
