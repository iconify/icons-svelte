<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o130g5b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="o130g5b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sparkle" {...props}></Icon>
