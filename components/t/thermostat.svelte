<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/q/qlgb7obud.css';
import '../../css/x/xtqu68bem.css';
import '../../css/d/d4tcmzeva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ud95brdct"/><path class="qlgb7obud"/><path class="xtqu68bem"/><path class="d4tcmzeva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:thermostat" {...props}></Icon>
