<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/guxh3kbks.css';
import '../../css/k/kxaa53mkw.css';
import '../../css/j/jne0vqbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="guxh3kbks"/><path clip-rule="evenodd" class="kxaa53mkw"/><path class="jne0vqbiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:street-view" {...props}></Icon>
