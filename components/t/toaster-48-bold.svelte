<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1efy3xti.css';
import '../../css/t/t1wq7pbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x1efy3xti"/><path class="t1wq7pbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toaster-48-bold" {...props}></Icon>
