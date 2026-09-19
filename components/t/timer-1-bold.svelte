<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fer6iobvf.css';
import '../../css/l/lh95obbwd.css';
import '../../css/h/hyu-j45la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fer6iobvf"/><path clip-rule="evenodd" class="lh95obbwd"/><path class="hyu-j45la"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-1-bold" {...props}></Icon>
