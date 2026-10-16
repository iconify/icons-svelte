<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz7_1-2mp.css';
import '../../css/n/nu73lppyk.css';
import '../../css/q/qffxtubht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fz7_1-2mp"/><path class="nu73lppyk"/><path class="qffxtubht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spray-can-48" {...props}></Icon>
