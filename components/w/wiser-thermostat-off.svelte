<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew8qlfbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew8qlfbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wiser-thermostat-off" {...props}></Icon>
