<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnjw03tfc.css';
import '../../css/n/nmjmojkvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nnjw03tfc"/><path class="nmjmojkvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silicon-48-bold" {...props}></Icon>
