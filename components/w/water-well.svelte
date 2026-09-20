<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ltbsbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3ltbsbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-well" {...props}></Icon>
