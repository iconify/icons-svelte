<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqoua65yl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/it6ujub8j.css';
import '../../css/g/ghj7d0a7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqoua65yl secondary"/><g class="dt0cm9dhy primary"><path class="it6ujub8j"/><path class="ghj7d0a7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-check-duo" {...props}></Icon>
