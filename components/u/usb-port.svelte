<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q574zqbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q574zqbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:usb-port" {...props}></Icon>
