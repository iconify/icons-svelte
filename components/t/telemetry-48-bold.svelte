<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6pxhx3fr.css';
import '../../css/b/bj9m5zbrg.css';
import '../../css/e/e13md-fck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i6pxhx3fr"/><path class="bj9m5zbrg"/><path class="e13md-fck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:telemetry-48-bold" {...props}></Icon>
