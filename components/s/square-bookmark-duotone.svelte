<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oh68e-fxv.css';
import '../../css/b/bgakwib_u.css';
import '../../css/s/s1a2eew1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oh68e-fxv"/><path class="bgakwib_u"/><path class="s1a2eew1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-bookmark-duotone" {...props}></Icon>
