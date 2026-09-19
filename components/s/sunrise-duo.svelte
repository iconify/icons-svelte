<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i5mjnubmu.css';
import '../../css/f/fc3wgfb7j.css';
import '../../css/a/ac6otnb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i5mjnubmu"/><path class="fc3wgfb7j"/><path class="ac6otnb7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sunrise-duo" {...props}></Icon>
