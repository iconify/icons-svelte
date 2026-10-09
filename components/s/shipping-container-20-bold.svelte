<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pufjjdbwp.css';
import '../../css/j/j2maz60ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pufjjdbwp"/><path class="j2maz60ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shipping-container-20-bold" {...props}></Icon>
