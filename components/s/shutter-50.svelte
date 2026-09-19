<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf36rwkpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf36rwkpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-50" {...props}></Icon>
