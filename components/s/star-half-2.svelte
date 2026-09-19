<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-70sba8t.css';
import '../../css/s/s9xtenb9b.css';
import '../../css/g/g_pe0ebql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-70sba8t"/><path clip-rule="evenodd" class="s9xtenb9b"/><path clip-rule="evenodd" class="g_pe0ebql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:star-half-2" {...props}></Icon>
