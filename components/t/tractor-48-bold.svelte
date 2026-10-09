<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfao_6b1t.css';
import '../../css/q/qepjo_bej.css';
import '../../css/t/t9qz5obke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rfao_6b1t"/><path class="qepjo_bej"/><path class="t9qz5obke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tractor-48-bold" {...props}></Icon>
