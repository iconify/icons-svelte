<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt8pu_u7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bt8pu_u7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:unlink" {...props}></Icon>
