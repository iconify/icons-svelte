<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf9z-jb7h.css';
import '../../css/a/ah_0o9bzq.css';
import '../../css/j/jih-r1b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rf9z-jb7h"/><path class="ah_0o9bzq"/><path class="jih-r1b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-bolt-48" {...props}></Icon>
