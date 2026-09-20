<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pz43xhblp.css';
import '../../css/e/efno7rbxx.css';
import '../../css/n/njxkp0atg.css';
import '../../css/b/b_6489u2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pz43xhblp"/><path class="efno7rbxx"/><path class="njxkp0atg"/><path class="b_6489u2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trellis-linear" {...props}></Icon>
