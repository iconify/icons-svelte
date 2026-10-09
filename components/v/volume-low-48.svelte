<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq2ynzhyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lq2ynzhyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-low-48" {...props}></Icon>
