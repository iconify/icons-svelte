<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6z3fnwdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6z3fnwdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:thermostat-v2" {...props}></Icon>
