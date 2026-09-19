<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx3jtcboz.css';
import '../../css/l/lu7xmg9vk.css';
import '../../css/w/wd2zr02fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx3jtcboz"/><path class="lu7xmg9vk"/><circle class="wd2zr02fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sunflower" {...props}></Icon>
