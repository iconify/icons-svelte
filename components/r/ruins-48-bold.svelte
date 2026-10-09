<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihmii9b0s.css';
import '../../css/s/shk-1412s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihmii9b0s"/><path class="shk-1412s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ruins-48-bold" {...props}></Icon>
