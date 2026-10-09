<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7sb8tbhe.css';
import '../../css/v/vj9dlzbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g7sb8tbhe"/><path class="vj9dlzbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toaster-48" {...props}></Icon>
