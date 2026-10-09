<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt41qcbim.css';
import '../../css/d/d122lmxog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dt41qcbim"/><path class="d122lmxog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-rain-20" {...props}></Icon>
