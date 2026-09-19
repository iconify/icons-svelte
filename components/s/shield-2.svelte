<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzhrqib3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="gzhrqib3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:shield-2" {...props}></Icon>
