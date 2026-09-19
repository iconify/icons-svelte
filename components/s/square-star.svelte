<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcd1uub9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="qcd1uub9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square-star" {...props}></Icon>
