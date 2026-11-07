<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4w_uybke.css';
import '../../css/w/wk2khdbwm.css';
import '../../css/f/fg8r_-gtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4w_uybke"/><path clip-rule="evenodd" class="wk2khdbwm"/><path class="fg8r_-gtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:washing-machine-minimalistic-bold-duotone" {...props}></Icon>
