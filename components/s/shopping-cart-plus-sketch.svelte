<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sj9gfcczj.css';
import '../../css/t/th_e4q71e.css';
import '../../css/l/lq53ewc5e.css';
import '../../css/r/rnkiedbvd.css';
import '../../css/z/zgkr20brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sj9gfcczj"/><path class="th_e4q71e wm-k"/><path class="lq53ewc5e wm-a"/><path class="rnkiedbvd wm-k"/><path class="wm-a zgkr20brz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shopping-cart-plus-sketch" {...props}></Icon>
