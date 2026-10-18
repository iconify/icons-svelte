<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0jwcy6ix.css';
import '../../css/x/xwae3tb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k0jwcy6ix"/><path class="xwae3tb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ufh-manifold-48" {...props}></Icon>
