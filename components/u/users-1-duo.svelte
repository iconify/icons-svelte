<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/acsrd_b0q.css';
import '../../css/e/e0u7ijb0l.css';
import '../../css/n/nj7wxyulw.css';
import '../../css/e/euq9bux1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="acsrd_b0q"/><path class="e0u7ijb0l"/><path class="nj7wxyulw"/><path class="euq9bux1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:users-1-duo" {...props}></Icon>
