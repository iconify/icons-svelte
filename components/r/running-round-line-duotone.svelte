<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lk387obkc.css';
import '../../css/o/ojeiq7bkf.css';
import '../../css/v/vrkxz3m8f.css';
import '../../css/a/apmotxbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lk387obkc"/><path class="ojeiq7bkf"/><path class="vrkxz3m8f"/><path class="apmotxbik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-round-line-duotone" {...props}></Icon>
