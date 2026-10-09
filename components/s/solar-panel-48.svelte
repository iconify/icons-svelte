<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laksrub_s.css';
import '../../css/n/n_odgsabd.css';
import '../../css/e/ejx72qubu.css';
import '../../css/n/nsnkgmbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="laksrub_s"/><path class="n_odgsabd"/><path class="ejx72qubu"/><path class="nsnkgmbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-48" {...props}></Icon>
