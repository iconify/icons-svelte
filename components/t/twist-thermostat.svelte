<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7rhuh1yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7rhuh1yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twist-thermostat" {...props}></Icon>
