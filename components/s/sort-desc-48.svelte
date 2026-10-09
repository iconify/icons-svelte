<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhifx_scc.css';
import '../../css/g/gyvla6x2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bhifx_scc"/><path class="gyvla6x2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-desc-48" {...props}></Icon>
