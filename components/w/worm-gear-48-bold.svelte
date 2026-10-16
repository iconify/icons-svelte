<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8spygx2w.css';
import '../../css/r/rjrkgcc1w.css';
import '../../css/l/lxpqrmtxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a8spygx2w"/><path class="rjrkgcc1w"/><path class="lxpqrmtxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:worm-gear-48-bold" {...props}></Icon>
