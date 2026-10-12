<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m4__4mvqr.css';
import '../../css/m/m0glyo1pp.css';
import '../../css/j/j_w-dobdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m4__4mvqr"/><path class="m0glyo1pp"/><path class="j_w-dobdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sparkles-duotone" {...props}></Icon>
