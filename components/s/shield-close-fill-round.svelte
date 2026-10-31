<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2eb40ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2eb40ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-close-fill-round" {...props}></Icon>
