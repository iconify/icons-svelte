<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7k1kge9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x7k1kge9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sliders" {...props}></Icon>
