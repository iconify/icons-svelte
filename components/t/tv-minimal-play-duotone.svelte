<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r3e-ge5gs.css';
import '../../css/u/uzmwkhbts.css';
import '../../css/p/p1cc6mb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r3e-ge5gs"/><path class="uzmwkhbts"/><path clip-rule="evenodd" class="p1cc6mb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tv-minimal-play-duotone" {...props}></Icon>
