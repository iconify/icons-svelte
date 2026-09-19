<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e2irt0b7x.css';
import '../../css/i/ihw3qzrvl.css';
import '../../css/p/pkn-bebts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e2irt0b7x"/><path class="ihw3qzrvl"/><path class="pkn-bebts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tsunami" {...props}></Icon>
