<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krwqt2j0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="krwqt2j0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wind-duo" {...props}></Icon>
