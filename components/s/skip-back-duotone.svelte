<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rry4zhb3e.css';
import '../../css/c/ckr17wbno.css';
import '../../css/b/buxgmoc6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rry4zhb3e"/><path class="ckr17wbno"/><path class="buxgmoc6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:skip-back-duotone" {...props}></Icon>
