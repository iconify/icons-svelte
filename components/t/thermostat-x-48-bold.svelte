<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmynvjkbh.css';
import '../../css/f/fdug528jx.css';
import '../../css/p/piqbfhj8g.css';
import '../../css/q/qnjenrxnq.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qmynvjkbh"/><path class="fdug528jx"/><path class="piqbfhj8g"/><path class="qnjenrxnq"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-x-48-bold" {...props}></Icon>
