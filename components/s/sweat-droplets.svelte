<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es_julb3f.css';
import '../../css/f/fffoeubbe.css';
import '../../css/d/dxbo5w2dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="es_julb3f"/><path class="fffoeubbe"/><path class="dxbo5w2dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:sweat-droplets" {...props}></Icon>
