<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi_htnp5m.css';
import '../../css/b/bvztumbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi_htnp5m"/><ellipse class="bvztumbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tether-usdt-line" {...props}></Icon>
