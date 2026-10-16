<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfegpe3kx.css';
import '../../css/e/ejhrpmb7e.css';
import '../../css/d/dl7nm1bnq.css';
import '../../css/i/ivnfvxbna.css';
import '../../css/v/vno_1ozcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nfegpe3kx"/><path class="ejhrpmb7e"/><path class="dl7nm1bnq"/><path class="ivnfvxbna"/><path class="vno_1ozcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-greenhouse-20-bold" {...props}></Icon>
