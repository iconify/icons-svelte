<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrz24nbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrz24nbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-cloudy-fill" {...props}></Icon>
