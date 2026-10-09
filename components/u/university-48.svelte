<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8vrn9u6r.css';
import '../../css/m/m3htm8bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r8vrn9u6r"/><path class="m3htm8bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:university-48" {...props}></Icon>
