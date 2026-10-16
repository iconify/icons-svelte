<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abgh_rbqn.css';
import '../../css/o/olx2f-b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="abgh_rbqn"/><path class="olx2f-b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scrubber-48-bold" {...props}></Icon>
