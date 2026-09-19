<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/skb8opsgk.css';
import '../../css/q/qel8s913f.css';
import '../../css/f/fvxa0x2ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="skb8opsgk"/><path class="qel8s913f"/><path class="fvxa0x2ag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:router" {...props}></Icon>
