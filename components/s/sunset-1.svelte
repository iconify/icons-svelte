<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7eta4bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="z7eta4bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sunset-1" {...props}></Icon>
