<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m417uzbhw.css';
import '../../css/l/l0mscrdyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m417uzbhw"/><path class="l0mscrdyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-charging-20" {...props}></Icon>
