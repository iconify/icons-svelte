<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iz383acsq.css';
import '../../css/v/vza56dhsg.css';
import '../../css/u/uxo0bkb9z.css';
import '../../css/d/dnfa3n46b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iz383acsq"/><path class="vza56dhsg"/><path class="uxo0bkb9z"/><path class="dnfa3n46b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-all-duotone" {...props}></Icon>
