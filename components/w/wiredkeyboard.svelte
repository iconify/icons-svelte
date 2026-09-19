<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiyaiv4lr.css';
import '../../css/t/tum1zw32k.css';
import '../../css/e/ech26lbaz.css';
import '../../css/p/pi4tf0brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kiyaiv4lr"/><path class="tum1zw32k"/><path class="ech26lbaz"/><path class="pi4tf0brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:wiredkeyboard" {...props}></Icon>
