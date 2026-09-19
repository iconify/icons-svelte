<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oil4e9epc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<rect class="oil4e9epc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:stop" {...props}></Icon>
