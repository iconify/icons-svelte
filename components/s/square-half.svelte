<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4wkd6b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z4wkd6b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:square-half" {...props}></Icon>
