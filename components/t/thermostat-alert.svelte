<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej1jc3dov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej1jc3dov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:thermostat-alert" {...props}></Icon>
