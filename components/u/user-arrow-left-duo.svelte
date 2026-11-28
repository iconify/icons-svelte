<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqoua65yl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/it6ujub8j.css';
import '../../css/m/mr42sub6s.css';
import '../../css/g/gyr8ovgjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqoua65yl secondary"/><g class="dt0cm9dhy primary"><path class="it6ujub8j"/><path class="mr42sub6s"/><path class="gyr8ovgjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-arrow-left-duo" {...props}></Icon>
