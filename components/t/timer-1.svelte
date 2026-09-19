<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s9rpw75hx.css';
import '../../css/v/v5q81xpom.css';
import '../../css/z/z873o0biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="s9rpw75hx"/><path class="v5q81xpom"/><path class="z873o0biu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-1" {...props}></Icon>
