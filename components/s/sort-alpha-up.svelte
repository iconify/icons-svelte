<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pgh9uxbqo.css';
import '../../css/q/qk7nzacnk.css';
import '../../css/f/f7f8lzgft.css';
import '../../css/k/keie_-blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pgh9uxbqo"/><path class="qk7nzacnk"/><path class="f7f8lzgft"/><path class="keie_-blj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sort-alpha-up" {...props}></Icon>
