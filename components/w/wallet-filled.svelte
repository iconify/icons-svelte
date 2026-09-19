<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkqky1bmv.css';
import '../../css/c/cps_4vb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkqky1bmv"/><path class="cps_4vb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wallet-filled" {...props}></Icon>
