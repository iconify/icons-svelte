<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzk1kzome.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzk1kzome"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tether-usdt-line" {...props}></Icon>
