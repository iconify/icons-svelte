<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz7umfcws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz7umfcws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scan" {...props}></Icon>
