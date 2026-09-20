<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rggt-cc5h.css';
import '../../css/z/zxnpu1bvo.css';
import '../../css/l/lqeh9j7ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rggt-cc5h"/><circle class="zxnpu1bvo"/><circle class="lqeh9j7ag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:shopping-cart-line" {...props}></Icon>
