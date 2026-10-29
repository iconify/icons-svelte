<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tzbq4-b0s.css';
import '../../css/w/ww85m-21c.css';
import '../../css/a/apviizbjs.css';
import '../../css/o/ocnol1b_l.css';
import '../../css/e/e7ft8bcmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tzbq4-b0s"/><path class="wm-a ww85m-21c"/><path class="apviizbjs wm-a"/><path class="ocnol1b_l"/><path class="e7ft8bcmq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shopping-cart-plus-duo" {...props}></Icon>
