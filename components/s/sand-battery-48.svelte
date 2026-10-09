<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnddocber.css';
import '../../css/e/ensp0mbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tnddocber"/><path class="ensp0mbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sand-battery-48" {...props}></Icon>
