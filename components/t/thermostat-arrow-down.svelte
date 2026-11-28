<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n004zgb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n004zgb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:thermostat-arrow-down" {...props}></Icon>
