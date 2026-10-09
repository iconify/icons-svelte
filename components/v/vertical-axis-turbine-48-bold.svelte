<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj5h1jbsa.css';
import '../../css/i/ih47sreee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fj5h1jbsa"/><path class="ih47sreee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vertical-axis-turbine-48-bold" {...props}></Icon>
