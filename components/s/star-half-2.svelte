<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/z/z4j9yhbxy.css';
import '../../css/z/zebdznrin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><path class="z4j9yhbxy"/><path class="zebdznrin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-half-2" {...props}></Icon>
