<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr_2ikhqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gr_2ikhqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:zero" {...props}></Icon>
