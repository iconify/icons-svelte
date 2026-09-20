<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsku83b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsku83b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:solar-power" {...props}></Icon>
