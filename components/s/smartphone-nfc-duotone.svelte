<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qr6_6tbrr.css';
import '../../css/i/is3hswbmz.css';
import '../../css/w/w4t23ybzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qr6_6tbrr"/><path class="is3hswbmz"/><path class="w4t23ybzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:smartphone-nfc-duotone" {...props}></Icon>
