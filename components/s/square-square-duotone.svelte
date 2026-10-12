<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nmzyjzk_e.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/o/ocri1_tge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="nmzyjzk_e"/><path class="s1a2eew1e"/><path class="ocri1_tge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-square-duotone" {...props}></Icon>
