<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o-2ja8zjz.css';
import '../../css/a/aeb7ubc3o.css';
import '../../css/l/l1lonvyyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="o-2ja8zjz"/><path class="aeb7ubc3o"/><path class="l1lonvyyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:volume-2" {...props}></Icon>
