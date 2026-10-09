<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3in-zb7w.css';
import '../../css/j/jtlfsbcyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z3in-zb7w"/><path class="jtlfsbcyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-thermal-48-bold" {...props}></Icon>
