<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr1zkm32g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr1zkm32g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shield-off" {...props}></Icon>
