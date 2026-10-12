<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fyoewac5c.css';
import '../../css/c/c37msdwqu.css';
import '../../css/j/jlkqa1bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fyoewac5c"/><path class="c37msdwqu"/><path class="jlkqa1bhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-note-plus-duotone" {...props}></Icon>
