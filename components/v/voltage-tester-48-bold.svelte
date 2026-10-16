<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrhhv18_e.css';
import '../../css/x/xo6w-xw4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nrhhv18_e"/><path class="xo6w-xw4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-tester-48-bold" {...props}></Icon>
