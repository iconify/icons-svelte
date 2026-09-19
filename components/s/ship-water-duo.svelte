<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lqpvglbyf.css';
import '../../css/o/o_4gfppxf.css';
import '../../css/s/s3pfium6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lqpvglbyf"/><path class="o_4gfppxf"/><path class="s3pfium6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ship-water-duo" {...props}></Icon>
