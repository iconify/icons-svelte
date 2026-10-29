<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/az90bnb8y.css';
import '../../css/l/l0xswydlb.css';
import '../../css/k/klpzb7dyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="az90bnb8y wm-deco"/><path class="l0xswydlb wm-k"/><path class="klpzb7dyr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ungroup-blueprint" {...props}></Icon>
