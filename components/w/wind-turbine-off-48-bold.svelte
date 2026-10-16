<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otu-ipbqt.css';
import '../../css/q/q1xmknq-a.css';
import '../../css/s/s50abdb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="otu-ipbqt"/><path class="q1xmknq-a"/><path class="s50abdb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-turbine-off-48-bold" {...props}></Icon>
