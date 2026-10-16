<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6h-ysber.css';
import '../../css/k/kxtdmfuan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c6h-ysber"/><path class="kxtdmfuan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:winch-48" {...props}></Icon>
