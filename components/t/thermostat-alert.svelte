<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q45a_2_uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q45a_2_uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:thermostat-alert" {...props}></Icon>
