<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lbuo8x34l.css';
import '../../css/k/kfkatubxd.css';
import '../../css/h/h56p5miuc.css';
import '../../css/l/l5p2-czkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lbuo8x34l"/><path class="kfkatubxd"/><path class="h56p5miuc"/><path class="l5p2-czkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vote-duotone" {...props}></Icon>
