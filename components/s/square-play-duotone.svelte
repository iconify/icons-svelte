<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dbqsfmbxh.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/e/eheeidcha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="dbqsfmbxh"/><path class="s1a2eew1e"/><path class="eheeidcha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-play-duotone" {...props}></Icon>
