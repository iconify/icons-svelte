<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2neunb3u.css';
import '../../css/j/j6w_1uvml.css';
import '../../css/p/plpbozbsh.css';
import '../../css/r/rycinhbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="j6w_1uvml"/><path class="plpbozbsh"/><path class="rycinhbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-48-bold" {...props}></Icon>
