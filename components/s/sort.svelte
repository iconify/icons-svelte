<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdx8_s66d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tdx8_s66d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sort" {...props}></Icon>
