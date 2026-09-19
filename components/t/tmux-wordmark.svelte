<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/onao27b_c.css';
import '../../css/d/dmeb_lbay.css';
import '../../css/k/kr4h8my1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="bi12bsetm"><path class="onao27b_c"/><path class="dmeb_lbay"/><path class="kr4h8my1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tmux-wordmark" {...props}></Icon>
