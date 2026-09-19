<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qx9a5vb2t.css';
import '../../css/m/mbdj0e04q.css';
import '../../css/j/jqrvh3_gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qx9a5vb2t"/><path class="mbdj0e04q"/><path class="jqrvh3_gi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:trash" {...props}></Icon>
