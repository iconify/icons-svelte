<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mslv4ubvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mslv4ubvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scarf-line" {...props}></Icon>
