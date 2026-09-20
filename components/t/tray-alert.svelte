<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt144hd_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt144hd_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tray-alert" {...props}></Icon>
