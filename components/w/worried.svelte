<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x_b7gqbqv.css';
import '../../css/f/fye1ff7ya.css';
import '../../css/u/ulnr9lfjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x_b7gqbqv"/><path class="fye1ff7ya wm-a"/><path class="ulnr9lfjv wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:worried" {...props}></Icon>
