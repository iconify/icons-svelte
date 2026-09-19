<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/am770-rkn.css';
import '../../css/v/vnl0nvbii.css';
import '../../css/s/smvgl5sak.css';
import '../../css/h/h9qr1objm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="am770-rkn"/><rect class="vnl0nvbii"/><path class="smvgl5sak"/><path class="h9qr1objm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sad-cry" {...props}></Icon>
