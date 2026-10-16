<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmynvjkbh.css';
import '../../css/f/fdug528jx.css';
import '../../css/p/piqbfhj8g.css';
import '../../css/q/qnjenrxnq.css';
import '../../css/o/ovk2mbcep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qmynvjkbh"/><path class="fdug528jx"/><path class="piqbfhj8g"/><path class="qnjenrxnq"/><path class="ovk2mbcep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-check-48-bold" {...props}></Icon>
