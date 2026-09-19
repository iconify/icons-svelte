<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ug5jgqb6q.css';
import '../../css/r/r1t8jr54z.css';
import '../../css/j/jncdp9blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ug5jgqb6q"/><path class="r1t8jr54z"/><path class="jncdp9blo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:spa-duo" {...props}></Icon>
