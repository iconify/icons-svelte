<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d4kcgfa-d.css';
import '../../css/c/c-6_08brp.css';
import '../../css/h/hbnz1c8ej.css';
import '../../css/m/mzhrmtosr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="d4kcgfa-d"/><path class="c-6_08brp"/><path clip-rule="evenodd" class="hbnz1c8ej"/><path class="mzhrmtosr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-alpha-down-outline" {...props}></Icon>
