<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b29jovbrz.css';
import '../../css/q/qol6ovbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b29jovbrz"/><path class="qol6ovbdp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlock-duotone" {...props}></Icon>
