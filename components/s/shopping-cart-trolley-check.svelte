<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2uru6-hq.css';
import '../../css/k/kqkpkcbdg.css';
import '../../css/f/flj_y0s4b.css';
import '../../css/u/ucsf5iwmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2uru6-hq"/><path clip-rule="evenodd" class="kqkpkcbdg"/><path class="flj_y0s4b"/><path class="ucsf5iwmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:shopping-cart-trolley-check" {...props}></Icon>
