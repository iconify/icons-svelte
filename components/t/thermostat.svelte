<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq7xt_-ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq7xt_-ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:thermostat" {...props}></Icon>
