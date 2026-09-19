<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qqt1bybxr.css';
import '../../css/p/p6va2jbdp.css';
import '../../css/h/htfz8x6gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="qqt1bybxr"/><path clip-rule="evenodd" class="p6va2jbdp"/><path class="htfz8x6gt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:speaker" {...props}></Icon>
