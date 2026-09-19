<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a0du3hboe.css';
import '../../css/k/kw3akl4eq.css';
import '../../css/l/l_wahk1-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="a0du3hboe"/><path class="kw3akl4eq"/><path class="l_wahk1-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:trophy-duo" {...props}></Icon>
