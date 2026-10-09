<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmuenm5kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qmuenm5kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-off-48-bold" {...props}></Icon>
