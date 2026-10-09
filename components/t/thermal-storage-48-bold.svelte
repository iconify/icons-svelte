<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9eadlwgv.css';
import '../../css/q/q_m60h3vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9eadlwgv"/><path class="q_m60h3vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-storage-48-bold" {...props}></Icon>
