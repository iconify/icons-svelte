<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiqnuhsan.css';
import '../../css/z/zzrqikhhv.css';
import '../../css/h/hb-shkb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qiqnuhsan"/><path class="zzrqikhhv"/><path class="hb-shkb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:synchronous-condenser-20" {...props}></Icon>
