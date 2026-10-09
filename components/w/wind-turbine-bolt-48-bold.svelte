<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocxzmlbuv.css';
import '../../css/w/wr0ronh9v.css';
import '../../css/z/zm910po5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ocxzmlbuv"/><path class="wr0ronh9v"/><path class="zm910po5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-turbine-bolt-48-bold" {...props}></Icon>
