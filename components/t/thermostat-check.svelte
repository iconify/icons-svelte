<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5f9tlanx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5f9tlanx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:thermostat-check" {...props}></Icon>
