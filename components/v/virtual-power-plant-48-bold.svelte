<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_ctiwi9q.css';
import '../../css/y/y_finwbhi.css';
import '../../css/l/lzsp7m9hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c_ctiwi9q"/><path class="y_finwbhi"/><path class="lzsp7m9hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:virtual-power-plant-48-bold" {...props}></Icon>
