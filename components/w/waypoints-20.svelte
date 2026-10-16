<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv9_vcbch.css';
import '../../css/g/glyz50bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pv9_vcbch"/><path class="glyz50bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waypoints-20" {...props}></Icon>
