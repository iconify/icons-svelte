<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/a/apidz6brj.css';
import '../../css/i/iji07ubvv.css';
import '../../css/z/z4n__z8-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="apidz6brj"/><path class="iji07ubvv"/><path class="z4n__z8-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:seek-skip-1" {...props}></Icon>
