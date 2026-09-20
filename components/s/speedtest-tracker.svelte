<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0q8t5bbo.css';
import '../../css/d/dmf_nf1iq.css';
import '../../css/f/fw-djbcff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0q8t5bbo"/><path class="dmf_nf1iq"/><path class="fw-djbcff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:speedtest-tracker" {...props}></Icon>
