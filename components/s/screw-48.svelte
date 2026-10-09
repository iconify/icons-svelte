<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnk74hkus.css';
import '../../css/k/kwnsnzbar.css';
import '../../css/k/k5ji0xe4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tnk74hkus"/><path class="kwnsnzbar"/><path class="k5ji0xe4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screw-48" {...props}></Icon>
