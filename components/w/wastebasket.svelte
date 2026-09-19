<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtfcmbcna.css';
import '../../css/r/rfp-f_hib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gtfcmbcna"/><path class="rfp-f_hib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:wastebasket" {...props}></Icon>
