<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mof-mqc8u.css';
import '../../css/z/z4rdixorf.css';
import '../../css/o/o3x5bbc6l.css';
import '../../css/t/tucir8lfq.css';
import '../../css/l/lik_usb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mof-mqc8u"/><path class="z4rdixorf"/><path class="o3x5bbc6l"/><path class="tucir8lfq"/><path class="lik_usb6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sunrise-1-bold" {...props}></Icon>
