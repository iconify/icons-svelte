<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dx4bavb6w.css';
import '../../css/h/h6wj0rbma.css';
import '../../css/u/u1l4v_kww.css';
import '../../css/w/w8nm51hzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="dx4bavb6w"/><path class="h6wj0rbma"/><path class="u1l4v_kww"/><path class="w8nm51hzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:shopping-bags" {...props}></Icon>
