<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv7_53bka.css';
import '../../css/m/m7ftp5n3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mv7_53bka"/><path class="m7ftp5n3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-thermal-48" {...props}></Icon>
