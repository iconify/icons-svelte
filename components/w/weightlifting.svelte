<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4q6eknm.css';
import '../../css/k/ksh1jl82n.css';
import '../../css/d/dm_j5gglv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="ksh1jl82n"/><path class="dm_j5gglv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:weightlifting" {...props}></Icon>
