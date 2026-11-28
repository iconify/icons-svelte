<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ou5voen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ou5voen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:thermostat" {...props}></Icon>
