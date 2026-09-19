<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaw_gqb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="aaw_gqb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-size-up" {...props}></Icon>
