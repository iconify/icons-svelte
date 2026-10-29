<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t8duj-sdt.css';
import '../../css/g/gybudlb5c.css';
import '../../css/u/ulnr9lfjv.css';
import '../../css/x/x_b7gqbqv.css';
import '../../css/f/fye1ff7ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="t8duj-sdt"/><path class="gybudlb5c wm-s"/><path class="ulnr9lfjv wm-s"/><path class="x_b7gqbqv"/><path class="fye1ff7ya wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:worried-duo" {...props}></Icon>
