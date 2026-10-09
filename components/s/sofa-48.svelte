<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m230b2b0n.css';
import '../../css/p/pg9gpuirh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m230b2b0n"/><path class="pg9gpuirh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sofa-48" {...props}></Icon>
