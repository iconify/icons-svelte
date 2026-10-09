<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw0sv1b2p.css';
import '../../css/o/ofyhu63mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iw0sv1b2p"/><path class="ofyhu63mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-48-bold" {...props}></Icon>
