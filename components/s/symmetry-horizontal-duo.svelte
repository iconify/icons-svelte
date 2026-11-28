<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5uw6ab1l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/okoh6nbnl.css';
import '../../css/e/egk2kv01d.css';
import '../../css/o/ormhxpb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5uw6ab1l secondary"/><g class="dt0cm9dhy primary"><path class="okoh6nbnl"/><path class="egk2kv01d"/><path class="ormhxpb2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:symmetry-horizontal-duo" {...props}></Icon>
