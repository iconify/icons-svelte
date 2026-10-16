<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyz2fo8fs.css';
import '../../css/q/q372t5bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kyz2fo8fs"/><path class="q372t5bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-charging-48" {...props}></Icon>
