<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqk7s7h9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqk7s7h9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:upload-network" {...props}></Icon>
