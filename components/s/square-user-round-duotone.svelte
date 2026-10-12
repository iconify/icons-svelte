<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hhi-gmoxu.css';
import '../../css/r/rgggbcbui.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/r/rgm6dncut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hhi-gmoxu"/><path class="rgggbcbui"/><path class="s1a2eew1e"/><path clip-rule="evenodd" class="rgm6dncut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-user-round-duotone" {...props}></Icon>
