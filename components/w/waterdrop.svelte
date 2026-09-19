<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mujumlinu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mujumlinu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:waterdrop" {...props}></Icon>
