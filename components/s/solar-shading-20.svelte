<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ivimbut.css';
import '../../css/f/fqx9z9z0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o3ivimbut"/><path class="fqx9z9z0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-shading-20" {...props}></Icon>
