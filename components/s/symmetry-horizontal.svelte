<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/okoh6nbnl.css';
import '../../css/e/egk2kv01d.css';
import '../../css/o/ormhxpb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="okoh6nbnl"/><path class="egk2kv01d"/><path class="ormhxpb2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:symmetry-horizontal" {...props}></Icon>
