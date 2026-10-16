<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_44j831n.css';
import '../../css/f/fjz8aybha.css';
import '../../css/m/mib1oqjfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m_44j831n"/><path class="fjz8aybha"/><path class="mib1oqjfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermocouple-48" {...props}></Icon>
