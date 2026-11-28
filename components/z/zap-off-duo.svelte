<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxpg3nbkx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kiwhpbcdm.css';
import '../../css/e/eo_76b8fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxpg3nbkx secondary"/><g class="dt0cm9dhy primary"><path class="kiwhpbcdm"/><path class="eo_76b8fd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zap-off-duo" {...props}></Icon>
