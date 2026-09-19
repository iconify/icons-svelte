<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n6o4-fb_f.css';
import '../../css/l/lefajib7x.css';
import '../../css/w/wai_u1bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="n6o4-fb_f"/><path class="lefajib7x"/><path class="wai_u1bew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sd-card-1" {...props}></Icon>
