<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpj3_ybqz.css';
import '../../css/w/wec04pbcz.css';
import '../../css/o/ota_86bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kpj3_ybqz"/><path class="wec04pbcz"/><path class="ota_86bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-direction-20-bold" {...props}></Icon>
