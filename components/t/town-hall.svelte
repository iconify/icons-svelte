<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb9k3_2ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb9k3_2ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:town-hall" {...props}></Icon>
