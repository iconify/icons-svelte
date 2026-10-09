<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogiazdbpv.css';
import '../../css/h/hkm130bnc.css';
import '../../css/x/xenj0gbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ogiazdbpv"/><path class="hkm130bnc"/><path class="xenj0gbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stadium-48" {...props}></Icon>
