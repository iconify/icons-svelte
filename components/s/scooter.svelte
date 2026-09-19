<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o7o3n1bzz.css';
import '../../css/f/fhtrc8bpo.css';
import '../../css/w/wernx2b0c.css';
import '../../css/c/c-aa9eqjn.css';
import '../../css/n/n5v6d8b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="o7o3n1bzz"/><path class="fhtrc8bpo"/><path clip-rule="evenodd" class="wernx2b0c"/><rect class="c-aa9eqjn"/><rect class="n5v6d8b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:scooter" {...props}></Icon>
