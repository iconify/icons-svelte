<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k2zyqvp7q.css';
import '../../css/c/chf8sacno.css';
import '../../css/o/oir1tjbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k2zyqvp7q"/><path class="chf8sacno"/><path class="oir1tjbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-100-duo" {...props}></Icon>
