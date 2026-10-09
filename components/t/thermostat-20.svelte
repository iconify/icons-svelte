<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/q/q-d9kh0tc.css';
import '../../css/m/m0qa3fayh.css';
import '../../css/k/kiknbdcxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="q-d9kh0tc"/><path class="m0qa3fayh"/><path class="kiknbdcxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-20" {...props}></Icon>
