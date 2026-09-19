<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jqs4cdc7m.css';
import '../../css/s/sq7tt6u1i.css';
import '../../css/o/ozlgx6bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="jqs4cdc7m"/><path class="sq7tt6u1i"/><path class="ozlgx6bya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-behance" {...props}></Icon>
