<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lk387obkc.css';
import '../../css/o/ojeiq7bkf.css';
import '../../css/q/q-3psc-ot.css';
import '../../css/c/c0rqgbbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lk387obkc"/><path class="ojeiq7bkf"/><path class="q-3psc-ot"/><path class="c0rqgbbqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-round-linear" {...props}></Icon>
