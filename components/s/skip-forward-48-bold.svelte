<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgxm3zihq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sgxm3zihq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skip-forward-48-bold" {...props}></Icon>
