<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s9oc3j10t.css';
import '../../css/f/f_d5gynxi.css';
import '../../css/i/i-loqsbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s9oc3j10t"/><path class="f_d5gynxi"/><path class="i-loqsbcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-duotone" {...props}></Icon>
