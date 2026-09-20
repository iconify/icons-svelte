<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n69kt-9eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n69kt-9eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-off" {...props}></Icon>
