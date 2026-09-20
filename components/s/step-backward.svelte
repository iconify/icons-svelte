<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks99qt2hl.css';
import '../../css/e/eh8-ivaqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks99qt2hl"/><path class="eh8-ivaqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:step-backward" {...props}></Icon>
