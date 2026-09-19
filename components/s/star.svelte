<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyhk58icw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hyhk58icw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star" {...props}></Icon>
