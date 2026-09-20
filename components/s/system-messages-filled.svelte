<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usmr1cmkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usmr1cmkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-messages-filled" {...props}></Icon>
