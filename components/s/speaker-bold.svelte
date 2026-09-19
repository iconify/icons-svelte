<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i6csbbc5i.css';
import '../../css/m/mjj5aehmb.css';
import '../../css/i/i67c3yb3a.css';
import '../../css/u/uk35fercj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="i6csbbc5i"/><path clip-rule="evenodd" class="mjj5aehmb"/><path class="i67c3yb3a"/><path clip-rule="evenodd" class="uk35fercj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:speaker-bold" {...props}></Icon>
