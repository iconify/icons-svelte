<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/p/p05fx7dxw.css';
import '../../css/n/nth_bib9h.css';
import '../../css/j/j7su0kpmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="p05fx7dxw"/><path class="nth_bib9h"/><path class="j7su0kpmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tuenti-logo" {...props}></Icon>
